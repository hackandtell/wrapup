# Cease fire! The war is over? (Hack and Tell Round 17: Wrap up!)

(Turns out, I have no idea when the Germanian war that started in
17 AD ended, but if you happen to know, feel free to reach out.[0])

Hello Hackers-

Thanks to [GetGlue](http://www.getglue.com) for hosting us! The
pizza was great, the drinks, they were sugary, and stickers oh so
gluey!

## Puzzle

Puzzle? Psshht! Puzzles take time to write, to do, and did I
mention someone has to *grade* them? Round 17 was too ad-hoc to put
that together, and the crowd that came would have aced it anyway.

I will, however, give you the answer to last month's wrap-upzzle[1]:

   (define (empty)
      (lambda (k)
         '()))

   (define (assoc dict key value)
      (lambda (k)
         (if (eq? k key)
            value
            (dict k))))

   (define (lookup dict key)
      (dict key))

   scheme> (lookup (assoc (assoc (empty) 'hello "world") 'world
"hello") 'hello)
   => "world"

## Projects Presented (in pseudo-random order)

### [Braindump] Malcolm Matalka (all the way from Sweden!)

Braindump is back![2] That's right, America's favorite Meetup (which
shut down to free up more time for Hacker School) has turned into a
wee-wittle segment at Hack and Tell--but hey, it's something! Want to
do a Braindump? Send me 3 blood samples, $5 US and a self addressed
stamped envelope. (Or, ask next time there's a call for speakers.)

This month, Malcolm was in town for Hack and Tell^W^W^Wa wedding, and
braindump'd a bit about what he knows of phantom typing in OCaml.

* [Phantom_types](https://github.com/orbitz/phantom_types)
* [Blog post](http://functional-orbitz.blogspot.com/2012/05/phantom-type-examples-in-ocaml.html)

### Nicolas Dufour

The Refuge Project aims to provide a fully decentralized and
open source data platform. What does that mean? Well, it means
that you'll have easy access to any data you shove into it.

* [refuge on GitHub](https://github.com/refuge/)
* [refuge.io](http://refuge.io)

### Grant Kot

Like Grant, I have like 3 words, awesome tentacle physics!

* [YouTube demonstration](http://www.youtube.com/watch?v=Za5_jBCuB0c)
* [Grant on GitHub](https://github.com/kotsoft)

### Peter Coles

Peter showed off his pure JS/CSS/HTML5 piano, which generates WAV
files that are then data-URI encoded. In other words, only ASCII data
is loaded from the web server, the rest, as they say is magic.

The visualizations were a little bit primitive, but hey, I guess
that's what you get for studying Computer Science instead of cello at
Julliard.

* [HTML5/CSS/JS Piano](http://mrcoles.com/piano/)
* [GitHub]https://github.com/mrcoles

### Zed Shaw

I mentioned during Round 17 that the reason Hack and Tell exists is
due in part due to the Freehacker's Union, which Zed created when he
lived in NYC. So having Zed stop by and see the community we've
created was certainly a treat.

These days Zed spends lots of time teaching programming by writing
books. They're freely available, but if you use them, and like them,
send him a few bucks so he can write more!

* [Learn Code The Hard Way](http://learncodethehardway.com/)
* [zedshaw.com](http://www.zedshaw.com)

### John Workman

Need to load hundreds of pictures in a web browser, but don't want
to bog down the experience? Well, scrollstream attempts to solve
this problem removing things from the DOM that aren't visible, and
loading new items in when they should be visible. It's dynamism at
its best!

* [Scrollstream](https://github.com/photoshelter/scrollstream)
* [John's GitHub](https://github.com/workmajj)

### Dan Vanderkam

Dan showed us dygraphs, an interactive, zoomable time series plotting
library for the web. It's pretty cool, supports oodles of data points,
has lots of tests *and* documentation. Really, it's like some holy grail
of software projects, which means if you have a use for it, you should
seriously consider it.

* [dygraphs](http://dygraphs.com/)

### Joschka Kintscher

Harvey allows you to do conditional JS loading via CSS media
queries. It has the concept of "Coins," which control how the JS is
loaded/executed. Personally, I'm just glad someone put a Dent into
this problem.

* [Harvey on GitHub](https://github.com/harvesthq/harvey)

### Aidan Feldman

Aidan talked about his JSONP proxy, which allows you to do JSONP with
*any* JSON API on the web. He could have saved himself some trouble
though, since the Meetup API supports JSONP[3]. Nevertheless, it might be
useful for someone else!

* [JSONP on GitHub](https://github.com/afeld/jsonp)
* [JSONP](http://jsonp.jit.su/)


## Announcements and things to watch out for

### Round 18 -- Coming soon!

Have something you'd like to present? Have something to Braindump?
Have a (free) space that can hold 80-100+ people and don't mind some
guests?  We're starting to plan Round 18, so let us know if you can
help us out! Call for presenters coming soon!

### Hope Number 9

HOPE is invading Hotel Pennsylvania yet again. This time,
it takes place on July 13-15. For tickets or more information
checkout [hopenumbernine.net](http://hopenumbernine.net).

## Wrap it up

That's it! Hope to see you all at Round 18!

Happy hacking,

Andrew and James.

[0]: Wikipedia has been lest helpful. (but, I didn't really look
     all that much... Yeah, my fault.
[1]: Have a more clever solution in a language that doesn't *have*
     closures? Share it!
[2]: ... and this time it's personal.
[3]: [Callbacks](http://www.meetup.com/meetup_api/#callbacks)
