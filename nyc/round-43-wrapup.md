# Round 43

Hello hackers,

Thank you to [Meetup](https://www.meetup.com/) for hosting us - I remember attending H&&T at Meetup headquarters 5ish years ago, and it felt great to come back home!

We have some big news to share, which those of you at round 43 already heard in person:

Sasha is leaving us, moving across the country (but surely not out of our lives <3)! We're going to miss her tons - she's put in tremendous work on arranging venues for our events, MCing, and getting shit done. Hack && Tell as we know it wouldn't be here today or run smoothly without everything she's done. Best of luck out west, and please come visit often!

Since Sasha is leaving town, John Hergenroeder is joining us as a co-organizer! He's smart, kind, and someone we trust to help keep things moving along around here. Thanks for jumping in to make H&&T possible!

Now, without further ado...

## The Hacks

### Max McDonnell - headless chrome webserver

Max showed us how to use a headless chrome instance as a web server. The hack accepts web requests, proxies them through a running chrome instance and allows for dangerous user-submitted code to handle the requests safely in the chrome sandbox.

* [Github](https://github.com/maxmcd/dcdn)


### Jeff Fowler - Sound From Nowhere

Jeff used an arduino and a speaker to create a musical instrument!

* [Sound From Nowhere](http://blog.jfo.click/sound-from-nowhere/)
* [Github](https://github.com/jfo/soundfromnowhere/blob/master/player/player.ino)


### Andrew Kelley - Zig

Andy has been working on his own programming language for a while now, and actually gave a presentation on Zig before! He came back to show us how partial compile time code execution works in Zig.

* [Zig Programming Language Blurs the Line Between Compile-Time and Run-Time](http://andrewkelley.me/post/zig-programming-language-blurs-line-compile-time-run-time.html)
* [Github](https://github.com/zig-lang/zig)
* [Twitter](https://twitter.com/andy_kelley)


### Wes Chow - text editor data structures

Know your tools! Ever wonder how your text editor manages the buffer, supporting efficient inserts, deletions, undo and redo features? Wes went over the common data structures involved: vector of lines, gap buffers, and chain tables.


### Jonathan Zacsh - Run Command On Changes

Jon shared the fun he had hacking together a "run on file-save" tool in (much like livereload, which is popular in nodejs webdev tooling) in golang.

* [Github](https://github.com/jzacsh/runonchange)


### Jess Frazelle - contained.af

Jess wrote a game to learn syscalls that uses a very restricted container. You can try to answer some questions to test and expand your knowledge, and also try to break out of the container! (No one has broken out yet, though, so GOOD LUCK WITH THAT.)

* [contained.af](https://contained.af/)
* [Github](https://github.com/jessfraz/contained.af)
    
    

## Announcements &c


### Round 44

We don't have a confirmed date for our next event yet, but we'll email the list as soon as we do. Thanks for your patience!

That said, please start signing up with presentations now, so we have a sense of who's interested. If the date ends up not working for you, you could always present at the next time instead. Tell us about your hack here: https://docs.google.com/forms/d/e/1FAIpQLSdGVWPlFA09Q1cyOlpoBioGsLtcqUrTC99n4fByPGPSUHNKCA/viewform?usp=sf_link

## Fin

As always, you can follow us on [twitter](https://twitter.com/hackandtell), and we'll let you know once we have a confirmed date for our next event ASAP!

Happy hacking,

&&{ aditya, danielle, john; sasha }
