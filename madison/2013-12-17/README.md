# Presentations

We had more systmes folks this time around, from distributed systems to computer architecture, plus a Python library.

## Leah Hanson
[Leah](https://github.com/astrieanna) presented a demo of [the game of life](https://github.com/astrieanna/distributed_gameoflife), implemented with distributed arrays in Julia, which allows it to run on a cluster as easily as a single machine.

## Jeshua Smith
Jeshua presented [a port of an OS from POWER/xlc/XCOFF to x86/gcc/ELF](jeshua_xlc_to_gcc.odp), which included having to porting a codebase where people called functions with missing arguments, reyling on a non-standards compliant compiler to fill in a default value, and having to convert inline assembly that was defined in a "standard" format that's the raw hex of opcodes to gcc's inline assembly format.

## Tom Wenisch
[Tom](http://web.eecs.umich.edu/~twenisch/) talked about [computational sprinting](http://acg.cis.upenn.edu/sprinting/), the idea of running chips very fast and hot and then giving them time to rest. He showed a demo with phase change materials (first wax, then an exotic metal alloy), which have much higher thermal capacitance than conventional cooling solutions, allowing chips to run much hotter than the thermal limit of the cooling solution for tens of seconds.

## Becky Gietzel
[Becky](http://pages.cs.wisc.edu/~bgietzel/) explained [CONDOR](http://research.cs.wisc.edu/htcondor/), a widely-used distributed computing system. She showed a visualization that allowed admins to figure out which jobs weren't running efficiently.

## Ian Cordasco
[Ian](https://github.com/sigmavirus24) showed off [Betamax](https://github.com/sigmavirus24/betamax/), his port of [VCR](https://github.com/vcr/vcr) to Python. It lets you replay network responses, allowing you to test web APIs without worrying about being rate limited by the web service you're using.

## Daniel Ross
[Daniel](http://www.math.wisc.edu/~ross/) showed off [mango](http://198.58.109.161:17143/suit/mango/), an IPC routing library that lets programs work together easily. His demo linked a web client with a command line program, and then put an encryption program in the middle.
