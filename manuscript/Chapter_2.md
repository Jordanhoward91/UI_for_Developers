#Chapter 2 Elements of Design for UI

##How to Analyze Typography for Software Systems

{width: 8, float: left}
![](jordan.png)

{width: 8, float: left}
![](jordan.png) In this section of the course, we're going to get into UI design elements. In this very first guide, we're going to be talking about typographic. This is something that I've personally seen as I've worked on projects especially a few of the projects lately where this seems like it's not a big deal until it's not done right.

I remember on the daily smarty project I implemented the full initial design and I had picked out the right fonts. Everything on the page was exactly where it should be. But there were some subtle changes such as I didn't match in the first draft the correct weight on some of the fonts and I would look at your design and then I'd look back at the screen and the screen was not good. It did not feel professional and even though it had 98% of the design matched. So this is something critical it's something I've seen that really separates an average design from something that truly looks perfect.

{width: 8, float: left}
![](jesse.png)

{width: 8, float: left}
![](jesse.png) Absolutely! This is the really fun stuff. These are going to be some exciting guides typography is awesome. I love typography and sometimes I hate typography. But good type theory makes a huge difference and that's why I wanted to start with this thing specifically. Typography can be extremely finicky, you can be one point away from fantastic looking pages or just garbage looking pages. The reason why it's not just one isolated piece of text is because type plays off of each other so much. By different font families or different weights or different sizes. Everything on that page needs to be talking to each other because if one thing doesn't belong if one thing is not doing what it's supposed to you know you might make that body text just one point bigger and it might not seem like a big deal but now all of a sudden all my headers don't properly take control of the situation. They've kind of like lost control of the body copy and they're not as bold as they need to be.

It just unbalances everything and honestly, if you're not thinking about typography you can be looking at a page and you're like I don't know what's wrong with it but something's wrong with it. There's a good chance it's the typography. It's something I run into with developers all the time where they think that close enough is good enough. It's not, it's got to be dead on.

If a design is ever delivered to you by a competent designer you need to match that pixel perfect especially the typography. If you're missing a weight or if the designer used a font that has a desktop license but there is no web version of it, don't just ignore it. And think "Agh, 700 will work. You've got to make sure that you are matching the weight and you might think it's just one-pixel different it's just one pixel of thickness, it can make a huge difference.

{width: 8, float: left}
![](jordan.png)

It really can, there's a very interesting story we keep on pointing to Apple because they've been a design lead in the industry for so long. But a lot of people don't realize that one of Steve Jobs greatest passions was calligraphy. He went to only a few classes in school because he wasn't a huge fan of the university and calligraphy was one of them and that was one of his big passions. And interestingly enough that is one of the first things he said he wanted in the operating system was the ability to have different types of fonts.

{width: 8, float: left}
![](jesse.png)

When they came out with the Apple Watch they found that Helvetica which they tend to use all the time didn't work well on it because everything was so small and so they made a whole new font San Francisco which they then implemented across everything it's like they're new Helvetica. But it was originally made to satisfy the needs of the watch because it was so small, and even though it's still really close to what they were using. There's just a teeny bit more space between the different characters. The wait is just a little bit more balance around each character. But they made an entirely new font just to satisfy a smaller screen size. And it was if they had just tried. I guarantee if you hack your watch and just implemented Helvetica in it then it would not look great.

{width: 8, float: left}
![](jordan.png)

Absolutely. We talked about the importance of it what are some steps that you take for being able to pick out the right types of fonts for applications you're designing.

{width: 8, float: left}
![](jesse.png)

Right, so you kind of have to start at understanding some basic typography principles. Understanding the difference between both Serif and Sans Serif fonts. Sans Serif is like when fonts have little things poking out from him. And then you're sanding those off right, let's think of it like that. You sand those off and you have a font like Roboto

![](https://s3-us-west-2.amazonaws.com/devcamp-pictures/UI+for+Developers/UI+Course+Introduction/How+to+Analyze+Typography+for+Software+Systems+%23+1263/image1.png)

Where every all the characters just stop they just end. Different fonts are going to work better in different instances. Now while there's a lot of rules with typography every rule can be broken with typography but there are some key things. For example, take dailysmarty. When we were designing that, all the headers, labels, things like. Those are all Sans Serif fonts. But the body copy, on a large post that's a Serif font because our eyes have a lot easier time reading Serif fonts especially in large paragraphs.

It's fine when you have a header or something like that. That's not to say that you can't have a body that's sometimes Sans Serif, I do it. I also have headers that are Serif fonts.

{width: 8, float: left}
![](jordan.png)

Devcamp uses Sans Serif fonts for the body.

{width: 8, float: left}
![](jesse.png)  

Yeah.

{width: 8, float: left}
![](jordan.png)

But Dailysmarty does the Serif and both of them look good just in different ways.

{width: 8, float: left}
![](jesse.png)

Right. And obviously and when we when did it with Devcamp like I said you can break those rules you can make them work but you have to be aware of it. And it's like OK but I've got to make sure that I'm at least using a Sans Serif font that isn't too close together that you know has really easily identifiable characters so that it's still going to be legible.

{width: 8, float: left}
![](jordan.png)

Absolutely. What are some tools that you use to be able to go through that and to see you know what they look like? like what heading looks like versus you know the paragraph and how well they're going to compliment each other?

{width: 8, float: left}
![](jesse.png)

A great place to start is [Google fonts](fonts.google.com). Not only are they really easy to implement and there's a lot of them and they're high quality and you don't have to pay for them. What's really nice is that they also show nice fonts that pair with each other.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

So you can see how to take Open Sans and how well Open Sans is going to pair with other fonts. It might give you some ideas. Now that's not to say a lot of Websites or a lot of apps will use the same font for everything and you can do that. You've got to use your weights accordingly. You've got to use your sizes accordingly. There's no reason why you can't use the same font for your headers and the same font for your body for subheaders or labels or things like that but Google fonts is a great place to start and there's lots of Websites that'll show nice font pairings but it's really nice because Google puts them right next to each other. You can implement both of them really quickly. It's a really helpful tool to use.

{width: 8, float: left}
![](jordan.png)

From a development perspective as well Google fonts was very nice because they also give you a download link if you're wanting to use it internally in your app. And they even give you a CDN option so you can just import it directly and then instantly have access right in all of your stylesheet so it's a nice all in one big solution.

{width: 8, float: left}
![](jesse.png)

Yeah.

As far as when you start laying out your page, that's something that's definitely critical. It's all nice when you can see, that fonts supposed to work with that one and then you just go. But there's so many variables between font sizes and weights it can get a little bit unwieldy pretty quickly right. So what you want to make sure you're doing is that when you're looking at your page when you're putting this page together this screen you want to say, OK labels, they need to draw the eye. Then I need to pull the reader into some other area. Sometimes you might have some metadata like say tags on a post for daily smarty.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

Those need to be there, they need to be smaller they don't need to command the situation. It's something that the user isn't going to be looking for immediately if it is you need to plan accordingly make them easier to find. You are implementing these ideas of what am I wanting the user to be looking at and what does the user want to find?

That's what kind of starts to drive. "OK, he needs to know where these tags are. But I don't want everyone seeing them". So it's taking over a more important thing like the description or whatever.

Maybe what you'll do is make the font smaller but you'll also gray it out just a little bit. Play with that. How's that balance? How's it looking? "OK, those are a little bit too out there". So I'm going to make them bolder but I am going to leave them grayed out. It's no hard and fast rule because you're going to be designing lots of different types of apps. But knowing the different variables you have to work with and knowing that it's important those are the biggest thing's you could take away from this is that typography is very important so don't just make it an afterthought. Really think about it and know that between the colors of your fonts the thickness is the size and the font families you can really control how prominent or how subtle a font is going to be on that screen.

{width: 8, float: left}
![](jordan.png)

That's a great point. For your homework I want you to take either an application that you've built before this or just spin up a couple of just plain HTML pages, go to Google fonts or one of these online font tools and bring down different combinations so bring down a font combination for a heading and a paragraph. Experiment with different weights and create a few different pages like this and then see how much of a difference it really makes. Explore both Serif and Sans Serif fonts and see how they can complement each other. Just so you can get into that habit of exploring those seeing what weights can do when you add that to a page and how you can emphasize different parts. And after you've done that then you can move on to the next guide.


##Strategies for Building a UI Color Scheme

{width: 8, float: left}
![](jordan.png)

As we continue on in this section on the elements of design for user interfaces
in this guide we’re going to talk about colors and how we can use colors how we can pick them out and we’re also going to get into some very practical sides on when we’ve had a few examples where the color was more than just something that looked pretty color actually determined parts of the user experience and how we have.

And this is why I think this is a very important guide is there is still a little bit I think of a mindset in many developers and just people in general that think designers make things look pretty. And that’s what they do. And that’s really all that there is to UI.

But for our case study, we’re going to go through. You’ll see that color determined the entire feeling that people had as they started going through this application. So it affected the user experience the business and how it looked.

{width: 8, float: left}
![](jesse.png)

Yeah. I love color, I think it’s so fun to pick what colors I would use in an app. I
really wanted to get a client who would let me design something completely purple. I haven’t done something all purple.

{width: 8, float: left}
![](jordan.png)

You weren’t hired by Yahoo?

{width: 8, float: left}
![](jesse.png)

Right!

I really love being able to plan out my whole color scheme for the app. When you’re doing that you’re going to be thinking of a few things. It’s not necessarily just like oh well I like this color so I’m going to pick it. You have the branding of that company or that product, or that specific project that you need to consider. You need to know how that color is going to behave in every aspect. A perfect example is on Devcamp, where were using a green color and it’s kind of a lighter color of green. We were seeing that any time that that color was a highlight color in text just text.

It’s really hard to see. It was really hard when it was on white it was just really hard to pick that that green was off. So we had to have another darker color green and a part of the style guide was hey any text when it goes green it needs to be this darker color or this darker shade than our branding of green. So you’re thinking of more than just oh this looks good. It’s how is this going to be used?

Sometimes I really like a lot of really subtle whites and grays. I don’t like really deep contrasts like 1995 style like really like deep contrasts between the whites and the grays. However, I’m working on a really nice monitor maybe not everyone will be.

{width: 8, float: left}
![](jordan.png)

Right

{width: 8, float: left}
![](jesse.png)

Bad monitors are really bad at separating like an f7f7f7 Gray from just a pure white. And they see them both as white and you’ll see that on projectors too.

{width: 8, float: left}
![](jordan.png)

Yeah

{width: 8, float: left}
![](jesse.png)

That’s why I make sure when I’m showing clients I like showing them on my monitor, not a
projector because it just looks like I just made an all white app.

{width: 8, float: left}
![](jordan.png)

Projectors make for some very bad types of demos for clients.

{width: 8, float: left}
![](jesse.png)

Yeah, exactly.

You’re thinking about a lot more than just necessarily what makes it look pretty. A really good tool for planning out your color scheme and we’ll put the Web site in and of course materials. But Paletton is a great Website where you can go in. You can put in a hex value and it’ll give you lighter and darker shades all inside of that same like color family.

It also shows you different shades or different colors complimentary things like that that you can use. A very common mistake that I see a lot of developers make when they’re coding a button say they have a green button and then they have an on hover color. And that on hover green it’s a different hue, a different shade is fine.

But it’s a more saturated green. So you’ve got this lime green going to a forest green and it just looks horrible. I go there every time. I never just arbitrarily pick a darker shade.
I’d go to Paletton and I get all my lighter and darker shades so I’ll use a lighter shade for maybe an inactive button and then the main shade for when it’s active and then a darker shade for when it’s hovered right so you really want to have this strategy throughout the app. These are the hovers these are the inactive states.

These are the main colors. And here we’re going to use mostly green but then occasionally we’re going to bring in a red or blue in very specific instances or maybe you’re an app that’s going to be using both and at the same time.

{width: 8, float: left}
![](jordan.png)

One example kind of going back to making sure everything’s pixel perfect. The one time with
Devcamp I was building out a screen that you had sent over and it had a button and everything matched except when I started using it something just felt a little bit different. And you the one that caught it and it turned out that the border of the button was just slightly different. And that’s what threw it off. We’re talking literally about a 1-pixel border. And it wasn’t even horrible it just threw it off and it made it feel not quite right.

{width: 8, float: left}
![](jesse.png)

It was fuzzy.

{width: 8, float: left}
![](jordan.png)

Just another example of how detailed it is and how important that is.

{width: 8, float: left}
![](jesse.png)

Don’t get mad at your designers if they’re being really nitpicky over stuff like that because it makes a big difference

{width: 8, float: left}
![](jordan.png)

It really does.

Just so you understand the process that when I’m working on a project with the Jesse he’ll send over the screens I will go implement them. Then as soon as I feel like they match from what I see I send it back to Jesse for a two-way process and he goes through and then sends notes. I never get upset when Jesse sends me notes back saying nope, nope, nope. These things have to be fixed because it does make a significant difference and on a first pass my eye may not pick those things up but you’re the one that built that design so you realized right away where the issue was. And that makes a huge difference.

{width: 8, float: left}
![](jesse.png)

Oh yeah.

A lot of times its not even necessarily things that I picked up from the beginning and then once I actually see it in use and I can hover over things and start to see how things actually work. All of a sudden it’s like whoa, my strategy was wrong.

I remember this one time I was actually at the gym and you called me and we had just implemented a screen that shows who you’re following on daily smarty and all the buttons of who you were following. So we’re looking at buttons and it’s like I want to follow someone so on hover goes blue you click it. Well now, what does the button do? After you’ve clicked the follow where does the unfollow button come from what does that look like? Originally we made the button red to unfollow it to differentiate it from the other follow buttons. But there was something really weird and we were looking at it and there’s something both of us don’t like about this screen

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

But we didn’t know what it was and what we realized was that what it’s doing, and this is it
shows the power of color, what it was doing is that all the people you were following had this big red gross thing next to them and it just felt negative.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

But these are the people you’re following these are the people you like most on this platform and they have this big like angry red button right next to them and it just didn’t feel right even though it was very functional that you’re like “Oh, I know where to go to click unfollow that person.” But it just didn’t make you feel good about looking at the people that you were following.

{width: 8, float: left}
![](jordan.png)

Right.

That’s such an important thing with color, red for one example, is something that is usually only used to signal that something bad happened. It usually is that an error happened on the page, or the form you submitted didn’t have the information that is needed and you need to go fix it. So typically red has that negative connotation in people’s minds. And what I really liked was for the dailysmarty example after we had that conversation Jesse recommended that we go and we start looking at how
other people were doing it. So going back to one of our first guides when we talked about getting inspiration.

The inspiration doesn’t just happen in the beginning it also goes along at each stage of
that development lifecycle. We went and we looked at Instagram and we’re like does Instagram turn the button red? No, in fact when you press follow. It automatically changes it to white and then allows you to message the person so there’s not that negative kind of connotation when you’re seeing your friends. Now old versions of Twitter used to have that same unfollow you’d click on follow it instantly turned the button red and then Twitter changed that eventually maybe for the same exact reasons why we changed it and that’s a great example it’s just a great case study for showing the importance of color
in an application.

{width: 8, float: left}
![](jesse.png)

Right, and it shows how user interface kind of interplays with user experience. Because you
are thinking of a couple of things at that point we have to ask ourselves the question. Well okay, so Instagram they don’t like leaving a bunch of unfollow buttons because they don’t want people gaming the system and they don’t want people going and just unfollow, unfollow, unfollow. They want to bury the button. I always am worried about talking about specific interface things.

Is that by the time people watch it because it might have changed but you have like go to the person’s profile and you have to unfollow. And so we have to ask ourselves do we want to purposely make it more difficult to unfollow people in mass no or maybe until we hit a certain critical mass. Let’s just make it as easy to use as possible so once you click follow maybe it goes blue with solid and then it says unfollow. It just changes the words but it doesn’t go red to connotate something bad.

{width: 8, float: left}
![](jordan.png)

Absolutely, and that’s really one of the main takeaways that I want you to get from this specific guide is that colors are much more than just some kind of palette on the screen. They are something that can help dictate that user experience and change the way that your users interact with the system. So I definitely recommend for you to go and check out some popular applications and note some of the different types of color schemes and palettes that they use. See how they use similar colors for things like you mentioned like for buttons and button hover effects and see the way they create that kind of combination. And then we’ll see you in the next guide.

### Resources
- Color Scheme Generator6
6
http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF

##Guide to Whitespace

{width: 8, float: left}
![](jordan.png)

In this guide we're going to get into another element of design: whitespace. This is something that I know is very near and dear to your heart, Jesse, because when we've discussed this, you've said if there is one thing that developers do not get about UI, in general, it is whitespace.

I'm probably guilty of this as much as anybody because usually when I think of whitespace I mainly just think of margin and padding, but it goes much deeper than that.

{width: 8, float: left}
![](jesse.png)

If there's one thing that I usually have to correct in design QA, it's whitespace. It's that they did not put enough padding between objects. It's because--and this is my own anecdotal guess--but it's not as practical. They say "I can still read all these and I can fit a lot more of them on a page," right?

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

But... since we learned how to *scroll* We don't necessarily have to be scared of scrolling. Now, that doesn't mean to throw caution to the wind and have all the whitespace in the world. You need to consider your constraints. Sometimes you're going to be X-axis constrained, and sometimes you're going to be Y-axis constrained. Whether that's because you're on a mobile device or you're like "Hey, we have to be really really meticulous with how much space we're putting on that axis, because maybe people are going to have really long usernames and we need to be aware of that." Or, "We have this table that needs to have five columns in it. How are we going to fit all those in?" And so it's not just saying "add all the whitespace." It's being aware of where you're adding it, cut it where you don't need it, but definitely add it where you do.

There's also times where you're going to be Y-axis constrained. For example, dashboards. Clients, a lot of times, say "I just want to open my phone or my desktop, and I want all my information *right there*. They might have a lot of information to show, so you have to be really meticulous about how big you make your fonts because you don't have a lot of space to work with.

However, you don't want to just shove everything in as tight of a space as possible. It's just not enjoyable to use. Users don't like it. It gives me anxiety! When you open up an app and everything is so tight, I'd rather scroll more and not feel like I'm going to have a heart attack the entire time.

{width: 8, float: left}
![](jordan.png)

Absolutely. And I've seen this even on some of the applications that we've worked on. Take DailySmarty for example. When I was just going with my own design, the main body of each post took up probably about 80 percent of the screen from left to right. And I hated the way it looked. I didn't know *why* I hated it. I just knew I was not going to enjoy reading it.

And then you sent the screens and brought in a lot of whitespace on the left and right sides. Going back to inspiration, it's very similar to how Medium does it, where a lot of whitespace is utilized on the left and right sides. You're completely focused as you're reading, and you just scroll down as you're going through that guide. Obviously it changes completely when you open up a guide on the phone. Then it has to go from pretty much edge to edge because you want to get all of that content. And that's part of responsive design, but it's a very subtle thing that makes a huge difference.

{width: 8, float: left}
![](jesse.png)

You'll actually notice when you go to DailySmarty and look at the index view, they're in cards, right? So I've got like a background going and I've got a card and then I've got the objects inside of that card. That works. It just feels really good when you have lists like that to have a card to frame the content inside of.

However, when you go to a post page, if I'm giving up whitespace outside of that card, and I definitely don't want to be pushing that text all the way to the edges of the card, so I put some padding there. Now this text is really skinny and it's really going to have a lot of scrolling.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

So a post page removes the card and makes the entire background white--again, similar to Medium, where it feels like the whole thing is just a piece of paper. And I liked that for a couple of reasons. One, I liked that you knew when you were on a post page. The font--that's where you see that san-serif come in. These pages are optimized for nice viewing. And it allowed me, since I removed the card and just made the whole background white, it allowed me to put in some nice big fat whitespace on the left and right. And it just reads so well.

You actually need to be aware of how many words--there's theories on how many words across there should actually be, because if you get too long the human mind just doesn't enjoy reading it as much. And so between making the font size bigger, bringing the margins in--the articles on DailySmarty just read really nicely.

{width: 8, float: left}
![](jordan.png)

Yes. And, in addition to DailySmarty, another good example of this, and it's one we've talked about, is how you can go to Apple's homepage or one of their product pages and you see that they just have very sparse content. They don't have an image on one side and then some text on another side. But then when I try to mimic that... it just looks like I haven't finished the site.

{width: 8, float: left}
![](jesse.png)

Haha. Exactly.

{width: 8, float: left}
![](jordan.png)

And a lot of that comes into organizing the whitespace and making sure that those types of components are placed in the right spot.

{width: 8, float: left}
![](jesse.png)

And I know we come back to Apple a lot. It's just a very good example because it's really easy to understand the reason why Apple does that so well. They're utilizing a couple different techniques. If you have that much whitespace and you don't have nice colorful images? That's what really brings a lot of that, like, *energy* into it. It's what keeps it from being sterile.

But then, also: fonts. They're making sure there's a lot of contrast between like a really dark thick font and the white. If you've got a bunch of grays on the whites and you don't have a lot of color going on, or you don't have people's profile images, a page can look really sterile. It's definitely a fine line. I think the misconception is just, like, you know, minimalism is just not putting very much on the page. It's not quite that simple. It's more refining, right? So it's being able to take our rugged rock and chipping off the things that are unnecessary until you have something that's nice and smooth. But it definitely requires using everything in your toolkit, because that whitespace, while it's really nice and makes things look really clean, if you're not using big bold typefaces or nice pretty images, it can make the page just look really sterile and unfinished.

{width: 8, float: left}
![](jordan.png)

As your homework for this guide I want you to go to the DailySmarty site and see the different types of ways that we implemented whitespace there. Then follow that up with going to places like Dribbble https://dribbble.com and Behance https://www.behance.net and see the way that other people have been building these types of user interfaces that utilize whitespace in all different kinds of ways.
