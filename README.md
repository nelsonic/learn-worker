learn-worker [back burner!!]
============

Everything you will ever need to know about Web Workers but didn't know you needed.

- - -

![Web Workers Banner](https://raw.github.com/nelsonic/learn-worker/master/images/web-workers-banner.png "Web Workers Banner")

- - -
>> if you're reading this, please just **skip to the links below**, 
this guide is not ready.
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

But JS was *still* stuck in *single-thread* mode which means 
calculation-instensive applications would block and show people 
error messages:

![Warning Unresponsive Script](https://raw.github.com/nelsonic/learn-worker/master/images/warning-unresponsive-script-jquery-fail.jpg "warning unresponsive script - javascript fail")

**HTML5 Web Workers** to the *Rescue*! These allow us to offload heavy processing to separate thread and ensure we do not "*block*" the user interface.

#### Basic Workers

**Todo**: think of a good (useful) *beginners* example to showcase WebWorkers.

(I used them for web-crawling @groupon but most novice developers are not 
going to see the point of a crawler, so need to think simple ...)


I'm de-prioritizing this tutorial for now because workers are not supported in 
the *default* Android Web Browser:

![Web Worker Browser Support](https://raw.github.com/nelsonic/learn-worker/master/images/web-workers-support-72percent.png "web workers browser support")

See: http://caniuse.com/webworkers (support 71%)


### Notes

#### Useful Links (Background Reading)

- Basic examples: http://www.html5rocks.com/en/tutorials/workers/basics/
- Mozilla (always a good place to get *detail*!): https://developer.mozilla.org/en-US/docs/Web/Guide/Performance/Using_web_workers
- Wikipedia article (quite thorough): http://en.wikipedia.org/wiki/Web_worker
- John Resig expands: http://ejohn.org/blog/web-workers/
- WHATWG (*living*) **Standard** for Web Workers: http://www.whatwg.org/specs/web-apps/current-work/multipage/workers.html
- W3C Candidate Recomendation: http://www.w3.org/TR/workers/
- Opera Dev Web Worker intro: http://dev.opera.com/articles/view/web-workers-rise-up/
- Transferable Objects (sending ArrayBuffers) to/from Web Workers: http://updates.html5rocks.com/2011/12/Transferable-Objects-Lightning-Fast
- 7 Things you Need to Know: http://www.developer.com/lang/jscript/7-things-you-need-to-know-about-web-workers.html


#### Non-essential + Trivia

- What websites looked like in 1997: http://royal.pingdom.com/2008/09/16/the-web-in-1996-1997/ (when I first started writing HTML... ;-)
- JavaScript Past & Future (Brendan Eich infoworld interview): http://www.infoworld.com/d/developer-world/javascript-creator-ponders-past-future-704
- DailyJS JavaScript History Lesson: http://dailyjs.com/history-of-javascript.html
- What websites looked like when they launched: http://www.telegraph.co.uk/technology/6125914/How-20-popular-websites-looked-when-they-launched.html
