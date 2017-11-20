# Chapter 3 UI planning

##Designing for Mobile and Desktop Environments

{width: 8, float: left}
![](jordan.png)
**Jordan Hudgens:**  Hi and welcome to the section on planning your user interface.

In this first guide what I want to talk about is the concepts of planning with desktop versus mobile because there are completely different considerations.

{width: 8, float: left}
![](jesse.png)

**Jesse Cook:** Right, absolutely.

This is something that definitely is becoming more and more important, as more things are being built for mobile. Almost every software application that we build is almost always required to have a mobile version of it, if not an exact clone. So there's definitely some very important considerations you're going to have when designing for both desktop and mobile, or just one independently, but definitely the interplay between the two.

So what's come out of this is the idea of mobile-first design. So when you hear that, the idea behind it is that you should start with the most constrained objects. So we should design for mobile first, because if we go to a desktop we have all this nice real estate to work with. We put in all these features and we put 10 features on one page which in *no way* is going to work on mobile. We have to completely re-imagine it. So if you start with mobile-optimized first it's a lot easier to go from there to desktop than to go from desktop to mobile.

![](https://s3-us-west-2.amazonaws.com/devcamp-pictures/UI+for+Developers/UI+Planning/Designing+for+Mobile+and+Desktop+Environments+/Jukebox+Desktop+UI.PNG "Jukebox Desktop UI")

{width: 8, float: left}
![](jordan.png)

Absolutely.

And we saw this with the Jukebox design where the designer on that built one of the coolest kinds of things I think I've seen in an application I was building, which was an actual jukebox for the desktop version. It looks like a jukebox. But that wouldn't translate directly to mobile and be too difficult to capture those gestures. And so being able to translate that properly is something you always have to take into account.

{width: 8, float: left}
![](jesse.png)

Yeah absolutely yeah.

And on desktop it's fine because you almost *want* to take up the space, because there's not necessarily a lot of objects on there. But on mobile you're going be giving up a huge percentage of your screen with those kinds of design elements. If you only give yourself this jukebox arch to work inside of, it's like "OK, that's fun, the desktop has this view, but for mobile we need to just make that a pure square and be able to just see it up at the top."

{width: 8, float: left}
![](jordan.png)

Absolutely.

Now how do you also take into consideration the difference between designing a true mobile app versus just a responsive web application. Because with a true mobile app you have access to other key APIs and those kinds of things, where with responsive web apps you're really just rearranging different content on the page.

{width: 8, float: left}
![](jesse.png)

Right.

Big things that you're dealing with there are menus: sometimes on desktop you're able to nest things inside of different pages, where on mobile that might be kind of difficult. Hover states: you don't have a hover state on a mobile device, right? So you know on a desktop you're like oh yeah. Well we'll show you this metadata--say you're doing an e-commerce app and you're wanting to hover over products, which flips a card and it shows some more information. Great now let's make that mobile. Now what do you do? You can't hover with your finger, so it's got to be something completely different. So you need to consider, well, maybe we need to have that metadata show on the desktop and then it'll stack underneath when it goes to mobile.

If I'm designing for desktop and I know that it's just going to be a responsive mobile page, it absolutely affects how I create cards, where I put data, how much metadata I even put on there. If I have five different pieces of metadata, I that know when it stacks it's going to be really confusing. Or it's going to be a situation where you're stacking picture on data on picture on data. How am I going to make that work?

That's one of the reasons why mobile first is so great, because if you can make it work on mobile, it can be a lot easier to make it work on desktop.

{width: 8, float: left}
![](jordan.png)

Absolutely.

And it seems like taking that mobile-first kind of approach would also help because your more complex types of gestures are on mobile. So being able to differentiate between someone swiping right versus someone scrolling versus someone clicking and pressing. There's all kinds of different options you can have. If it's a native mobile application, you even have gestures like  shaking the phone to do something. There's all kinds of different things that you have to take into account. Whereas, it's much easier to translate those into something on the desktop because then you have a lower number of items.

{width: 8, float: left}
![](jesse.png)

Right.

Like I was saying earlier, say, on a desktop, drop down nav works really well, but maybe it's not going to work so well on mobile because the text might be too small. Maybe there's so many things in that dropdown that it's going to drop below your scroll, and then you're in a really weird situation. So that's why a lot of mobile applications use a hamburger menu. You're constantly thinking, "How exactly am I going to make this work?"

And then there's development considerations, right? Like how you structure the menu on desktop and now when you put that into mobile it might make page load times higher or there's a lot of different things you're probably thinking about there.

{width: 8, float: left}
![](jordan.png)

Absolutely.

Another thing, not to throw a wrench into all of it, but what about tablets? That's something in between desktop and mobile. When you're designing an application, you have the much smaller mobile app with gestures and a very small screen, and then you have your desktop version which doesn't have gestures, has a large screen and you can perform all of your main hover actions, but a tablet is a cross between the two. You have more space--maybe a little constrained--but then you have those gestures. What type of approach do you take with tablets to optimize for that?

{width: 8, float: left}
![](jesse.png)

I mean, honestly, you also don't even know how big of a monitor someone is working with on the desktop. That used to be our biggest problem. We were just like "Oh man, we've got all these desktop sizes" and then we had to go and add a bunch of very very small and mid-size displays as well, right? So that's definitely where you see a lot of design principles that make it more ubiquitous. It doesn't matter what size screen it's going to be on, it's going to adapt accordingly.

Instead of designing out 10 different desktop sizes, 3 different iPad sizes, 10 different mobile phone sizes, it's better to just have a methodology. Like, whether you use cards that are going to stack really nicely, or dividers, it's about using things that are just going to be able to adapt all the way across that gammut. It's more about finding the principles as opposed to designing out every single screen.

{width: 8, float: left}
![](jordan.png) Absolutely.

For your homework for this guide what I want you to do is to pick out a number of popular applications, such as Facebook, Twitter, Wall Street Journal, and watch how they change between these different environments. Go to the desktop version, see what it looks like there, then try it on your tablet if you have one. Then access it on your smartphone and see the way they adjust. Look at both their responsive web sites and also the mobile applications themselves, because you'll see a lot of changes and some very strategic changes for, not only user interface, but also just for the user experience itself and how they access different parts and different features.

For example, Facebook makes a very big focus around how you can post, and they make it very easy to post, when you are on your phone. They give you much quicker access to working with images and your camera because it has it right there. Whereas, typically, you don't upload as many images straight from your computer so it doesn't get emphasized as much.

So go through, look at all of those kinds of examples. That should also start giving you some inspiration for how you will build the user interface for your own desktop and mobile apps.


##How to Create an Effective UI Style Guide

{width: 8, float: left}
![](jordan.png)

This is going to be a really fun and practical guide because we're going to talk about building a style guide.


{width: 8, float: left}
![](jesse.png)

This is where it's important to be detail oriented. I think this is right in line with keeping your room clean and keeping copious notes of your design.

{width: 8, float: left}
![](jordan.png) Haha.

{width: 8, float: left}
![](jesse.png)

The important thing here, again, is communication. The communication process is critical to make sure that these designs are going to be realized the way that you want them from the developers and vice versa. You need to be able to, as a developer, understand how to interpret the notes of a designer, if they're provided. So what's really important is to identify objects and fonts and things like that, which are going to be used throughout the app. You want to identify those different things because you want continuity throughout the app. You want to make sure all your headers are going to be the same.

You want to make sure your buttons are always looking the same, and that they're not of different widths, or they're not of different font sizes. Things like that. So they all behave the same, right?

So what you're doing is you're saying "OK, I know that this is the button that's going to be used throughout the app." And you add it to the style guide. You say, "Here is button active. Here is button inactive. Here is button after clicked. Here's button on hover."" You need to make sure these things are documented for when you pass it to a developer, so that they don't have to keep coming back and asking you what that looks like.

{width: 8, float: left}
![](jordan.png)

What tools do you use in order to communicate that?

{width: 8, float: left}
![](jesse.png)

First of all, for designing these screens, I use Sketch https://www.sketchapp.com, which I do specifically because of its integration with InVision https://www.invisionapp.com. And InVision is a fantastic product that you can subscribe to that allows you to take your designs and share them with the developer, and then the developer can inspect your designs in a way that is very similar to the inspection tool in a browser.

It'll show you styles, font weights, and all these things that are extremely helpful, as opposed to just delivering someone a PDF. It's much better than just eyeballing everything, because we all know how well that goes. It's fantastic to be delivered screens in an InVision prototype, because you have all the information right there. That isn't to say you don't still want a style guide where they can set up their CSS styles and they can just call in that button or call in an H1 or whatever.

{width: 8, float: left}
![](jordan.png)

Absolutely. This is something on the developer side that I do have quite a bit of experience with. When you give me a set of styles and give me the screens, one of the very first things that I'll do is, using a tool such as Sass, create a set of variables in the application. I just create a file called `variables` and then I will name them. So for DailySmarty, for example, we have that very specific kind of blue. I created a variable called `$dailysmarty-blue` and then saved the hex color that you sent over.

![](https://s3-us-west-2.amazonaws.com/devcamp-pictures/UI+for+Developers/UI+Planning/How+to+Create+an+Effective+UI+Style+Guide/Sass+Color+Variables+File.PNG "Sass Color Variables File")

Then, everywhere in the application, and in all of the other Sass files, I can just call the `$dailysmarty-blue` variable. I don't have to go and reference that Hex color every single time. And then I do the same for every color in the style guide.

I also copy the style guide. Especially if it's extensive. With DailySmarty, it wasn't that massive, so I could contain everything inside of the Sass file, but devCamp has a very large one.

So I'll add them to application's README, and whenever I have a question about it, I can just check the README. I put the name of the component, the name of the variable I used in the Sass file, and the actual value of the variable itself, just so that I have everything right in front of me. It's a personal preference, but I've found it to be pretty effective.

{width: 8, float: left}
![](jesse.png)

When you're creating this style guide, it's important to be flexible. You should definitely lay out your colors, font families, headings, and things things like that beforehand, but you'll be hard-pressed to make it through an entire application without some adjustments. Modern design programs make it easy to define these variable and then tweak them application-wide, all at once, which is very handy.

Don't go crazy diverging from it, but don't be so rigid that it keeps you from designing a good looking page.

{width: 8, float: left}
![](jordan.png)

Yes, absolutely. 

The homework for this guide is: go to some type of application--it could be a popular one like Facebook or Twitter--and create a style guide for that application. This would be very similar to the process you would do if you had just finished building the user interface and then went and checked to see what all those styles were. See what the heading font size is, what the colors are, the background colors, all of these different types of components, even getting down very granular into border radius. That makes a huge difference. Just making sure that each one of the edges of your divs are rounded in the right way.

So go and build that and we will see you in the next guide!
