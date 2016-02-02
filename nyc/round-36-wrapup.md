# G'morning Hackers!

Thanks for coming out to H&&T 36! The event was graciously hosted and fed by [Dev Bootcamp](http://devbootcamp.com/). We love going there. The projector and audio always works, they have their own Code of Conduct, and they're such nice people.

If you'd prefer to read rendered markdown, [go here](https://gist.github.com/jmsdnns/e410ff28487224ff2305).

## Smart Hacker Wants A Job!

Before we enumerate the presentations, we wanted to put the spotlight on Faraz Fazli, our last presenter. Faraz is just 18 and presented a blogging platform he built in Go. It was so well done that we nearly didn't let him present because we were convinced he was trying to demo a product. Turns out he built a fantastic tool for the Go community because he just wanted to and then got [CacheFly](http://www.cachefly.com/) to donate the resources for hosting it, including DDoS protection and a worldwide CDN.

He showed his age when he sent me his resume and asked me to forward it to the list. We're not gonna subject him to the nonsense of NYC's recruiter networks, but after seeing him present we think any shop that needs a Go hacker or Android hacker (he does that too!) should hire Faraz.

People that know H&&T know we don't say this lightly. We've never actually put the spotlight on someone looking for a job before, but Faraz carries the hacker spirit as much as any of us and he's just getting started.

You can reach him at [farazfazli@gmail.com](mailto:farazfazli@gmail.com).

_Faraz, don't say yes to the first thing you see. Remember that you're interviewing them as much as they're interviewing you. Find a group of people that you can learn a lot from and would enjoy spending a lot of time with. And be skeptical of recruiters. Ideally, some hackers will reach out to you directly instead._

## The Hacks

### Aaron Schumacher - Sonic Histograms

It's histograms for your ears! It's made with R! Aaron's work literally processes histograms to make audio. Weird and amazing, just like most of the hacks Aaron has presented.

Fun fact: Aaron helps organize the Hack && Tell in DC.

* [project](http://planspace.org/20151214-hearing_data_with_sonic_histograms/)

### Dan Vanderkam - Source Map Explorer

Dan built a tool to figure out why your JavaScript bundle has gotten so darned big. It's great for debugging duplicated sources and surprising dependencies which have crept in. 

Also worth mentioning that source maps are not downloaded unless the browser debugger is opened. _Thanks to the hacker in the audience who asked the question that clarified this._

* [src](https://github.com/danvk/source-map-explorer)

### Oliver Friedmann - fixme

We have all been there (probably many times a day). We execute a command, and it fails.

In some cases we know how to fix it, and in others we know how to google for a fix. Most of the time, the fix is simple, but it is still a time suck to get it fixed.

Fixme solves this issue by simply checking command outputs against a database of fixes. If there is a fix, it generates the fixing code, which can depend on parameters of the actual command.

* [src](https://github.com/oliverfriedmann/fixme/)

### Gregory Gundersen - Slate

Mobile-first web app to track personal expenses. He built it because he often make small cash purchases that he doesn't track, he has no idea how much he spend per month on things like food or alcohol and worries it might be a lot [_we understand -Ed_], and programs like Mint.com seem too complicated.

You can try it [here](http://gregorygundersen.com/slate/) with username:guest password:hack&&tell, but add/edit/delete are disabled for guest.

* [src](https://github.com/ggundersen/slate)

### A. Jesse Jiryu Davis - MockupDB

Jesse wrote a MongoDB wire protocol server in Python. You can use it to impersonate the MongoDB server! To demonstrate, he connected from the mongo shell to his fake database, and manually responded to client queries as if it were a server.

* [docs](http://mockupdb.readthedocs.org/tutorial.html)
* [src](https://github.com/ajdavis/mongo-mockup-db)

### Steve McCarthy - Gotoblaze

Gotablaze is a dota2 league game information api aggregator. What that really means is, it's a project that reads the fabulously undocumented dota2 api, grabs the current state of the games, and diffs and then saves it (in RethinkDB!). It repeatedly does this to get a slow set of snapshots of the game states. Eventually, one will be able to view these slow set of snapshots in real time! Like http://www.trackdota.com/ but without all the pretty graphics.

* [src](https://github.com/ifo/gotablaze)

### Faraz Fazli - GotGoBlog

As mentioned above, Faraz developed a blogging platform in Golang which lets users easily make blogs and write. he made the entire thing over the course of 2 days for the GopherGala hackathon and have been working on it since then.

_Reminder: Faraz is looking for a job!_

* [GoBlog](http://www.goblog.pw/)
* [src](github.com/getgoblog/goblog)

## Fin

Thanks again to [Dev Bootcamp](http://devbootcamp.com/)!

We also appreciate how many folks recently offered us a spot to host Hack&&Tell. We will be building a system for people to submit locations soon. In retrospect, it's ridiculous we haven't had one, huh... ¯\\\_(ツ)\_/¯ So it goes...

See everyone again soon!

&&{ aditya, danielle, james, sasha }
