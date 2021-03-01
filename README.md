# yaccety_path
Elixir DSL for yaccety_sax document parsing

## Idea
yaccety_sax is a streaming XML pull-parser for the BEAM. 

Pull-parsing means, a process is in no way forced to handle all events that come to it. 
Things can be skipped, the stream can be terminated early, and each event can cause the parser to go into a new state, call a new function, or do whatever it well pleases.

A process can handle more than one stream at a time. Grab 2 events from that one, 3 from this, and return them all to this other thing. Whatever you want. That's the fun part, and entirely up to you!
No more getting on the "callback train" that never lets you get off until the stream is done.

## Current status of this repo
This repo is for idea gathering and brainstorming at the moment.

Later, it will be a repo full of really beautiful code!

But, for now, a place for people to share ideas and help come up with a fantastic way to use a small DSL to scrape data at blazing speeds from XML streams in Elixir!

Now, wait?? Just Elixir?? No. But a nifty DSL is maybe easier to hash out in Elixir. After that, an Erlang version will definitely be coming. :-)

## Got something to add?
Start a [discussion](https://github.com/zadean/yaccety_path/discussions)!
