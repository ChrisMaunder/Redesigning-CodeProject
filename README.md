# Redesigning CodeProject

Rethinking the design and layout of CodeProject.com using the design language formerly known as Metro.

## Introduction

The design of CodeProject has changed over the years, as one would hope and 
expect. The design, however, was often a result of expedience over planning and 
as such it often became, well, a little haphazard and often more thought was put 
into cramming as much as possible on a page instead of thinking about what 
should actually be on a page.

A common complaint of the site - in fact, *the* complaint regarding the 
site, was that the look was old, tired, and cramped. You hit the site and you're 
bombarded and confused. We loved the old look, though, in the same way a dog 
loves it's old, scuffed up shoe that it drags around everywhere. It was comfy. We 
knew how it worked. It had everything we needed. 

And yet...

And yet we were looking for a change, and the motivation came from an issue 
that many developers share: we were running out of hours in the day and we 
needed to cut down on the things we were doing and things we maintained. This 
lead us to remove some parts of the site that were not being used by many 
members (I'm guessing you probably haven't even noticed their departure) as well 
as trimming down the feature sets of other parts to make them simpler to use.  
Doing this started us down the track of thinking about what each page was meant 
to do, and more importantly, what each page should not do.

We also started focusing on the articles themselves since they are what keeps 
us at CodeProject passionate. Safari's "Reader" mode made a big impression on us 
since it allows you to focus on the content, not the chrome, and that theme was 
one we kept coming back to. Make the content the most important thing on the 
page, and give the content room to breath. Fairly simple ideas, and, 
conveniently enough, ideas encapsulated in the Metro Design language that 
Windows 8 was built on.

## A stroll down memory lane

2000, soon after launch

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2000_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2000.PNG)

2005 - evolution has occured. 

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2005_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2005.PNG)

2008 - our biggest redesign

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2008_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2008.PNG)

2011 - clearing out some debris

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2011_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2011.PNG)

## The Design Language Formerly Known As Metro

I'm not a fan of many of the implementations of Metro that I see around. I 
caught a glimpse of the CodePlex redesign before it was live and it was 
beautiful. However, at launch it seemed to have all character washed out of it, 
and noise had crept in. I completely understand the compromises they had to 
make, however, and so I started wondering if we could or should do our redesign 
using the Metro philosophy. 

### Initial requirements

Our initial requirements were pretty simple

1. Obviously CodeProject
2. Easy to read
3. Everything we need to show goes on the pages.

I explain item 1 by using the example of a developer walking past another 
dev's desk. When someone walks past someone else's desk and glances at their 
screen, they should know instantly that the page is showing a CodeProject page. 
I want to be loud and proud. I do not want another design that is distinguished 
from the others only by something such as text link colours.

Item 2 is obvious, but item 3 is where the real work begins, and it involves 
some subtleties. Does all content on a page need to actually be visible all the 
time? Can it be shown in a flyout or dropdown? Or a tab? Or a click-through? 
Where should it be shown - above or below the fold? 

An important aspect of item 3 is to place our information in a hierarchy. 
Decide what's most important, then next important, and so on down to the least 
important. It focuses your thoughts wonderfully.

### What's important

Articles, obviously, but also our community, discussions and questions and 
answers. Articles first, though. Always articles.  On the homepage we want 
to make it clear what is possible, but it's pointless trying to show off 
everything - a mistake we were making in the past. Besides, the homepage is not 
the most popular page on the site, the articles are. Readers don't Google or 
Bing us (is that a verb yet?) and go to the homepage. They go to an article or a 
question. If we need to highlight something then the article page is the place 
to do it.

### What do we want our readers to do?

Read lots, submit lots of articles, enjoy themselves and click our 
advertiser's ads like they are going out of fashion. All very simple, but how do 
you achieve this?

The obvious answer is you guide your readers to actions you think will 
benefit them (or benefit the site)., but this simple requirement is one I see 
ignored on site after site - and we were guilty too. The bible in this regard is 
the book [Don't Make Me Think](http://www.sensible.com/dmmt.html), 
and so we needed to provide instant guidance for new readers still looking to 
get their bearings.

### Design patterns

Putting this together our requirements were

1. Promote the branding
2. Promote the content, reduce noise
3. Relax the layout - less cramped = easy to read and find things
4. Provide guidance

Take a quick look at the philosophy behind Metro and you see it's based on 
two core things:

1. Content over Chrome
2. The use of negative space (ie whitespace)

Metro is no about tiles. That's an implementation of Metro used on touch 
devices. I'm really not a fan of this outside of a touch environment, and having 
seen it overused again and again I was initially hesitant to go down the Metro 
path. Further, the examples we had seen were washed out and bereft of branding. 
If we were going to do this we'd have to stay focused on what we needed, not 
what had been done before.

## Wireframes

This seemed a fit so we started putting together some wireframes to explore 
the ideas. 

The first one shows the initial ideas and is, essentially, the direction we 
chose to go. There was lots of talk of the links being orange, of the top bar 
being too orange, and of the spacing being way too big in comparison to the font 
size, but the idea is there: Say what you need to say and no more. Keep it 
clean.

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/wire1_sm.PNG)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Design2011.PNG)

This then evolved into a more familiar form:

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/wire2_sm.jpg)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/wire2.png)

We had some fundamental issues with this. It was laid out nicely, it was 
clean, but it was boring. The soul was lacking, and most importantly, it was 
giving us a headache trying to read orange on white. The debate raged on and 
finally we reached a compromise and moved to dark headings.

On top of this there was a concern that the tiles on the homepage were 
exactly what I didn't want: large blocks that really served no purpose other 
than to take up screen space. They were adjusted.

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/wire3_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/wire3.png)

However, now the issue was that it was impossible to see which items were 
links and which weren't. Eventually blue links were brought back and arrived 
where we are today.

## The big issues

We've tried redesigning the site a number of times since our last redesign 
and they all failed because we were trying to hold on to our old way of doing 
things instead of starting with a clean sheet. We were trying to skin instead of 
redesign, and that will never solve fundamental information architecture issues. 
Once we were down the path to thinking about the content as the primary focus, 
and in directing our readers to that content, things fell together very, very 
quickly and the biggest issues turned out to be the smallest. What icons do we 
use? Do we even use icons? How much padding between articles? What background 
colour for the forums? And the biggest headache, what colour for the links.

Below is what we wanted to do. I love it. Absolutely love it. But it gives me 
a headache. A grey/orange combo does not shout "fresh" or "read me when you're 
tired". It whispers, insidiously, "eye strain". So the compromises happen.

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/latest_articles_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/latest_articles.png)

## What really changed?

Fundamentally not a lot, but in essence, everything. The homepage saw the 
biggest shakeup (or shakeout, really) and the article pages were the most 
drastically streamlined. 

## Progress in pictures

Once the designs were finalised and the mockups submitted it took me 115hrs 
over a 9 day period to implement the CSS, layout and backend code changes. I use 
.LESS extensively and so took the opportunity to break our monolithic CSS file 
into smaller chunks that were more easily manageable. I cannot recommend .LESS 
highly enough. It's what CSS should be. 

Primary work was done using Firefox / [Firebug](http://getfirebug.com/), and then Chrome and it's dev tools, and finally IE, especially
[IETester](http://www.my-debugbar.com/wiki/IETester/HomePage). 
Graphics were done using an aging, creaking version of Fireworks (I know, the 
shame) and coffee was provided by [Te Aro](http://www.te-aro.ca/).

Here's small small screen grabs of progress for your amusement.

Initial skinning. Argh. My eyes.

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Progress1_sm.png)](Progress%201.PNG)

A close to final version showing dim headings and orange links

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Progress2_sm.png)](Progress%202.PNG)

An initial draft of the new article page. This required a little replumbing, 
but considering the extent of the changes there wasn't a huge amount to do on 
the backend.

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Progress3_sm.png)](Progress%203.PNG)

And a close to final version. Tags still had outlines, the top nav menu was 
still being finalised, and heading sizes were going up and down like a yo-yo 
that day. Caffeine levels were getting dangerous.

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Progress4_sm.png)](Progress%204.PNG)

The final screen grab is from 30 mins before launch. For crispness we 
wanted dark links so the entire page looked clean and consistent, but in the end 
the potential confusion around which links are clickable and which are not 
outweighed aesthetics. 

[![](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Progress5_sm.png)](https://raw.githubusercontent.com/ChrisMaunder/Redesigning-CodeProject/master/docs/assets/Progress5.PNG)

## A final word

When designing it was critical that we not only had a firm goal in mind, but 
a clear understanding of what we felt was most important. At every step we asked 
"do we need this" and actively tried to remove items we felt didn't add value.

This design update is just the beginning of our latest round of changes and 
we don't expect this design to settle in comfortably for at least a couple of 
months. We'll always find loose ends, and we still have a TODO list of minor 
pages and design elements we didn't get a chance to finish. We love your 
feedback, especially the "yay, we love it", but we understand it's not to 
everyone's liking.

But we ask you to do this: let it sink in. Give it time.
