# Round 39: Consecutively Prime

Hello hackers,

Thank you to everyone who presented, showed up, asked questions, and made round 39 awesome! 

And a huge thank you to [Dev Bootcamp](https://devbootcamp.com/) for hosting us and providing food and drinks!

Without further delay...

## The Hacks

### Tom Ballinger - Dal Segno

Tom created a tool where you can write games and see your changes immediately - every time you change your code, Dal Segno rewinds your game back to the last time that piece of code was run. (That last bit was super cool. Tom spoke about how wanting the rewinding to be useful changed the way he structured his code.)

And then he showed us a language you might use on a ship - Shiplang! - and a spaceship game where each ship has its own interpreter - MissileCMD!

(He didn't write the Javascript interpreter the game uses, but he modified it to be forkable, resumable, and to have native async functions. And then he put it in pretend spaceships!)

Tom adds: "The enemies in this game still use Scheme interpreters which I did write, but the player's ship and missiles use JS interpreters."

We have no idea how Tom managed to fit so much stuff into just 5 minutes, but it was a helluvan opening act.

* [Github (Dal Segno)](https://github.com/thomasballinger/dalsegno)
* [Github (shiplang)](https://github.com/thomasballinger/shiplang)
* [Github (interpreter)](https://github.com/thomasballinger/hotswapping-js-interp#js-interpreter-with-hot-swappable-functions)
* [MissileCMD](http://march8prototype.ballingt.com/?simulator)
* [Twitter](https://twitter.com/ballingt)


### Paul Biggar - hkrn.ws

Paul's project has no code - which is the point! He wrote a URL shortener for Hacker News which didn't use any code at all - the hack is that he used a CDN's builtin URL rewriter (ie Cloudfare page rules) instead!

Since the number of bugs in your project is best predicted by the number of lines of code you've got, and this project has none, we figure Paul just proved himself pretty damn good at creating reliable, bug-free software.

* [blog post explaining Paul's hack](https://hackernoon.com/the-tech-behind-hkrn-ws-f311e69459dd#.ncjzdtogz)
* [Twitter](https://twitter.com/paulbiggar)


### Brian Lee - MuGo

Brian presented a pure Python implementation of the essential parts of AlphaGo (a Go/Baduk/Weiqi AI based on a neural network).

We learned that training the policy network to predict human moves was sufficient to get MuGo to about 1 kyu! For human comparison, that'd make MuGo a weaker player than Brian, and a tiny skinch stronger than Danielle.

* [Github](https://github.com/brilee/MuGo)


### Michelle Steigerwalt - i17on

i17on is intRAnationalization engine for Markdown. (Apparently the term i18n was already taken. ;)

In other words, i17on is a text preprocessor which allows you to write dynamic documents using a simple tag-based language.

Basically, you can write a flexible document once with tags defining how you want the language to change based on the audience, and then generated different versions of your document by disabling/enabling various tags.

It's a great tool for writing a resume that you can quickly tailor to different types of jobs, and also for putting off job-hunting in favor of working on interesting tooling instead!

If you're looking to get started contributing to free software, Michelle emphasized that there's low-hanging fruit issues that you can work on, and we totally bet she'd be helpful and encouraging along the way.

* [i17on](http://i17on.com/)
* [Github](https://github.com/Yuffster/i17on)
* [Twitter](https://twitter.com/Yuffster)


### D. Schmudde - Rhythm of Time

How do you compose a documentary about a musician for an audience that may not be super familiar with how electronic music works? Schmudde solved that by writing a music step sequencer for web browsers. In Clojurescript!

* [The Rhythm of Time](http://rhythmoftime.xyz/)
* [Github](https://github.com/schmudde/rhythm-of-time)
* [Twitter](https://twitter.com/dschmudde)


### Vaibhav Sagar - git internals workshop

A git internals workshop...
Implemented as a scripted git repository...
Using V's own git library written in Haskell.

The git repo itself IS the workshop. V was trying to figure out how to create the repo, and then remembered that he'd already implemented git in Haskell, so he could just use that to craft the repo! So he wrote a script for constructing its own git history with his git implementation.

* [Github (workshop)](https://github.com/vaibhavsagar/git-internals-workshop/)
* [Github (duffer)](https://github.com/vaibhavsagar/duffer)
* [Twitter](https://twitter.com/vsagar2109)


### Pedro Ha - Labas

"Labas" means "hello!" in Lithuanian. It's also the tool Pedro wrote to help you learn Lithuanian!

Rather than requiring lots of clicking around (like the site where Pedro found the audio translations), Labas auto-scrolls within each section to keep your language skills moving along.

Pedro showed us good design, and also a nifty trick for thinking about web performance - audio sprites! Just like with regular ol' image sprites, you can join multiple audio files into one big audio sprite to reduce the number of downloads you need for your site.

* [Labas](http://labas.surge.sh/)
* [Github](https://github.com/pedroha/labas)
* [presentation slides](https://docs.google.com/presentation/d/1JdTqElmRF69NMLIVX-KFhovNED8bR0fxX93TbTyZf5g/edit#slide=id.p23)


### Max Cantor - Scopey

It's really hard for new programming students to figure out what all the terms mean. Have you ever tried googling "var"? It doesn't get you very far if you don't know to try "var KEYWORD" instead.

To solve this problem for his students, Max wrote Scopey - a teaching & learning tool to help programming students explore and understand the hundreds of jargon words and interrelated concepts that get dumped on them when they learn a new language.

Scopey uses vanilla javascript, no jquery or other frameworks, and prints out explanations of the terms that you mouseover.

As a bonus, Max showed us the learning tool he wrote for himself to help him write this learning tool for others!

* [Github](https://github.com/mcantor/scopey)
* [Twitter](https://twitter.com/mcantor)


## Announcements &c

### Donations

Thanks to everyone who contributed towards our group donation to the [Software Freedom Conservancy](https://sfconservancy.org)! Aditya will be making a $269.31 donation to them, which will help them keep on protecting and supporting free software!

As always, while we're happy to keep donating to the Conservancy, we're also happy to hear any suggestions you might have of other organizations that keep the hacker spirit alive that we should put into a donation rotation as well.

 
### Venues needed!

We need venues! If your company has space to host us, please PLEASE [get in touch](mailto:nyc@hackandtell.org)!

What's in it for them? Well, you can point out that we strictly forbid all recruiters and company-focused talks, carefully vetting our speakers and moderating the mailing list to keep that stuff out, with the sole exception being that we let our host speak for a few minutes at the beginning of the night.

Hosting us is a fairly low price to pay for the exclusive right to pitch y'all for just a moment. ~.^

Or, y'know, they could do it out of the goodness of their hearts. We like that too.


### Round 40

We're aiming for early December, but our next venue fell through, so we can't announce the date until we have a new venue confirmed. As soon as we get a venue sorted out, we'll announce the date on the meetup mailing list.

## Fin

As always, you can follow us on [twitter](https://twitter.com/hackandtell)!

Happy hacking,

&&{ aditya, danielle, sasha }
