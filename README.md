learn-worker [WORK-in-PROGRESS!!]
============

Everything you will ever need to know about Web Workers but didn't know you needed.

- - -

If you've never heard of **Web Workers**, 
prepare to **ignite your imagination**!

### What is a Web Worker and Why do I Need One?

#### 30 Second JavaScript History Lesson 

**JavaScript** was designed in **1995** (by 
[Brendan Eich](http://en.wikipedia.org/wiki/Brendan_Eich))
to be 
[single-threaded](http://en.wikipedia.org/wiki/Single_threading) 
(only run one command/function at a time).
I mention the date because *back in 1995*, the web was rather primative.
The types of "programs" that were written in JavaScript were limited to 
"interactivity" (prompts, alerts and pop-ups), roll-over buttons and other
web [frosting](http://en.wikipedia.org/wiki/Icing_(food)) which didn't 
actually *do* anything. 

To give you and idea, this is what the Apple website looked like in 1997:
![Apple Home Page 1997](http://farm4.static.flickr.com/3251/2862869896_2396cb3524_o.jpg "Apple Website in 1997")

**1995 to 2005** were the **Dark-Ages** of the web, 
[Browser Wars](http://en.wikipedia.org/wiki/Browser_wars) meant many features
were only available in one browser *Internet Explorer* but not in others. 

In Feb 2005 Jens & 
[Lars Rasmussen](http://en.wikipedia.org/wiki/Google_Maps) 
released [Google Maps](http://en.wikipedia.org/wiki/Google_Maps#2005) 
which sparked a revolution in JavaScript applications that came to be know
as "**Web 2.0**" (essentially "*New*" JS-based websites with 
real *functionality* not just sugar water).

Also in Feb 2005 [Jesse James Garrett](https://twitter.com/jjg) wrote 
an article about **XMLHttpRequest** (which allowed web browsers to 
*dynamically* load data/content and update the page *without refresh* 
(coining the term "*AJAX*" to describe this seamless user experience).
At this point JS gradually emerged from obscurity and people began 
building *useful* things.

But we were *still* stuck in *single-thread* mode...







>> I don't have time to work on a proper tutorial/article right now. 
So if you're reading this, just skip to the links below. :-) ...tbc!

### Notes

#### Useful Links (Background Reading)

- Basic examples: http://www.html5rocks.com/en/tutorials/workers/basics/
- Mozilla (always a good place to get *detail*!): https://developer.mozilla.org/en-US/docs/Web/Guide/Performance/Using_web_workers
- Wikipedia article (quite thorough): http://en.wikipedia.org/wiki/Web_worker
- John Resig expands: http://ejohn.org/blog/web-workers/
- WHATWG (*living*) **Standard** for Web Workers: http://www.whatwg.org/specs/web-apps/current-work/multipage/workers.html


#### Non-essential + Trivia

- What websites looked like in 1997: http://royal.pingdom.com/2008/09/16/the-web-in-1996-1997/ (when I first started writing HTML... ;-)
- JavaScript Past & Future (Brendan Eich infoworld interview): http://www.infoworld.com/d/developer-world/javascript-creator-ponders-past-future-704
- DailyJS JavaScript History Lesson: http://dailyjs.com/history-of-javascript.html