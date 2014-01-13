# Round 18: Wrap Up, Schmap Up

(Have a complaint about this email? Want to make it better, fix
a typo, or add more info? Fork the gist on GitHub!
https://gist.github.com/3187335)

Hello Hackers-

Thanks to [Meetup](http://www.meetup.com) for hosting us! They've
supported us since the very beginning, and of course are amazing
hosts!

## Boo! No Puzzle.

We should really bring these back. They're lots of fun. Have a
puzzle that you'd like to challenge us with? Email us, and maybe
we'll include it in the next wrap up, or as an RSVP challenge[0].

## Projects Presented (in pseudo-random order[9])

### Andrew Kelley

Andrew showed us chem, an HTML5 game engine/toolkit which makes
building HTML5 games fast. This guy is completely legit. I know
this because IcedCoffeeScript is one of the supported languages.

Though he failed to live-code a demo (and who wouldn't?), he did
woo us with his port of Dr Chemical's Lab.

* [github](https://github.com/superjoe30/chem)
* [Dr Chemical's Lab](https://github.com/superjoe30/dr-chemicals-lab)

### Max Krohn

Max showed us One Shall Pass, a pure client side Javascript,
and cryptographically strong solution to the password problem.
You memorize one moderately long pass phrase, and let One
Shall Pass compute a password for you.

Of course, it can't always be that simple, so One Shall Pass
supports different security settings, an option for adding
symbols, and a generation parameter which allows you to always
use the same base password, but change the computed password,
for when LinkedIn's db gets broken into again.

* [One Shall Pass](https://oneshallpass.com)
* [source](https://github.com/maxtaco/oneshallpass)

### [Braindump] Andrew Gwozdziewycz

Andrew spent five minutes feverishly attempting to explain the
One Pass Real-Time Generational Mark Sweep Garbage Collection
algorithm that Erlang used in the mid-90s.

* [slides](http://bitly.com/ht-braindump-gc)
* [actual implementation](https://github.com/apgwoz/surd) (most
  likely broken)

### Nicolus Gattuso

We saw a quick and dirty Arduino hack from Nicolus, who is using
his $97 in parts to light up some LEDs when some websites are
down. Of course, the learning experience (he's a first time
hardware hacker) is well worth the $97, and it is a cool idea.

* [github](https://github.com/DietCoder/ArduinoServerStatus)
* [parts list](http://www.sparkfun.com/wish_lists/45090)

### Nathan Hamblen

Nathan showed us herald, a simple way to publish release notes
for a project to a central place (supports Tumblr only right now).
While it's written in Scala and used by the Scala community now,
it's built in such a way that other communities could easily
adopt it as well.

* [notes.implicit.ly](http://notes.implicit.ly)
* [github](https://github.com/n8han/herald)

### Andrey Fedorov

Bitcoin seems to be all the rage these days, and Andrey presented
a Bitcoin wallet that you can use within Chrome. It seems to use
Twitter's Bootstrap heavily (sigh), but I can honestly say,
Bootstrap and Chrome extensions go well together.

* [chrome extension](https://chrome.google.com/webstore/detail/hfdeddmpdncodjalbadbanlcombfeoll)
* [source](https://github.com/andreyf/electrum-wallet-chrome-extension/)

### Jordan Orelli

Jordan's favorite pastimes are (in no particular order), building
things to make sound, and telling everyone how much he loves the
Go programming language. While I could do without the latter, I
love seeing what he comes up in regards to the former.[1] This
time was no exception, but come on man, we need more than one
color! (Note: This hack wasn't done in Go (surprise!), it
actually used some C++)

* [multitone](http://github.com/jordanorelli/multitone)

### Francis Gulotta

When new HTML5 features like [WebRTC](http://www.webrtc.org/) are
combined with OpenCV, funny images from the Internet, and a little
bit of caffeine, you get You Laugh, You Lose, a silly game in
which you attempt to not laugh before your opponents.

(I don't see the source, so I've linked to his GitHub profile in
hopes that it'll appear)

* [You Laugh, You Lose](http://ylyl.jit.su)
* [github](https://github.com/reconbot)

### Ken Amarit

Ken quit his cushy job to follow his passion of making video games.
The twist? He doesn't just *draw* graphics, he uses the delicate
fine art of needle felting, and the tedious process of stop motion
animation. Voyager is his first game, due out soon on iOS.

* [Voyager](http://ohmy.me/voyager)

## Announcements and Things to Watch out for...

### Round 19 - Coming Soon

We'll need a place to meetup, a pizza sponsor and lots more great
hacks. If you can help with any of that, let us know!

### Battle of the Braces

Meetup is holding a series of Hackathons--there's still time to
get in on the fun [Battle of the Braces](http://www.meetup.com/Battle-of-the-Braces/).

### Maker Faire New York 2012

Don't know what Maker Faire is? Well, you'd better check it out!
[Maker Faire](http://makerfaire.com/newyork/2012/)

### Coder Weekly

I don't get much time to read the web these days, so I've been
relying more and more on a weekly mailing list called
[Coder Weekly](http://coderweekly.com/). It gets sent every
weekend and has a good mix of interesting articles.

## Tie a bow...

Until next time!

Happy Hacking,

Andrew


[0]: "Oh man, those first four hundred bites of dirt were not so
good. Maybe the next one will be better. WHAAAT is this? Some sort of
a challenge buried in the GROUUUND? Lookie hear! A power crunch!
Tastes like a #1 jam!" -- Strong Bad Email #115

[9]: [Dilbert on randomness](http://dilbert.com/strips/comic/2001-10-25/)

[1]: While I do write Go professionally, I'm not as fond of it as
Jordan by any stretch of the imagination. If you're looking to
avoid C/C++ or want to stop worrying about jars, but still get
the benefits of garbage collection (albeit a horrible one), you
should check out Go. However, you'd probably be much better off
learning to write really clean, idiomatic Haskell, as the people
behind it are some of the smartest programming language people
that have walked the Earth. Though, personally, I much prefer a
dynamically typed Lisp-1 such as Scheme.
