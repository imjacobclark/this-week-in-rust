Title: This Week in Rust 84
Date: 2015-06-22
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](http://rust-lang.org) is a systems language pursuing the trifecta:
safety, concurrency, and speed. This is a weekly summary of its progress and
community. Want something mentioned? Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) or [send us an
email](mailto:corey@octayn.net?subject=This%20Week%20in%20Rust%20Suggestion)!
Want to get involved? [We love
contributions](https://github.com/rust-lang/rust/wiki/Note-guide-for-new-contributors).

*This Week in Rust* is openly developed [on GitHub](https://github.com/cmr/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/cmr/this-week-in-rust/pulls).

This week's edition was edited by: [Brian Anderson](https://github.com/brson), [Vikrant Chaudhary](https://github.com/nasa42), [Andrew Gallant](https://github.com/BurntSushi), and [mdinger](https://github.com/mdinger).

# From the Blogosphere

* [Exceptional results: error handling with C# and Rust](https://ruudvanasseldonk.com/2015/06/17/exceptional-results-error-handling-in-csharp-and-rust). Exceptions based error handling in C# vs Rust's monadic approach.
* [Rust Torrent](http://pietro.menna.net.br/recurse-center/rust/2015/06/19/rusty-torrent/). Pietro Menna shares his experiece of writing a BitTorrent client in Rust.
* [Exploring Rust](http://www.wilfred.me.uk/blog/2015/06/18/exploring-rust/). A brief look at state of affairs in Rust 1.0.
* [Rust using Visual Studio Code](https://mobiarch.wordpress.com/2015/06/16/rust-using-visual-studio-code/). Setup Visual Studio Code for Rust development.

# Tips & Tricks

* [How to pass a closure into a trait object](http://camjackson.net/post/rust-lang-how-to-pass-a-closure-into-a-trait-object).
* [Rust error stacktraces](http://phildawes.net/blog/2015/06/17/rust-stacktrace/). Get stacktrace from errors in production code.
* [Benchmarking in Rust with `libtest`](https://llogiq.github.io/2015/06/16/bench.html).

# In the News

* [Google Bazel added support for Rust](https://github.com/google/bazel/tree/master/tools/build_rules/rust).
* [Impala: a Rust dialect that can partially evaluate functions at compile time and produce GPU code](http://compilers.cs.uni-saarland.de/papers/ppl14_web.pdf).
* [Rust: Announcing the community subteam](https://internals.rust-lang.org/t/announcing-the-community-subteam/2248).

# New Releases & Project Updates

* [RustLex](https://github.com/LeoTestard/rustlex). Lexical analysers generator for Rust.
* [rsedis](https://github.com/seppo0010/rsedis). Redis re-implemented in Rust.
* [cargo add](https://github.com/withoutboats/cargo-add). A utility for adding cargo dependencies from the command line.
* [volley](https://github.com/jonhoo/volley). A benchmarking tool for measuring the performance of server networking stacks.
* [Rust Dispatcher](https://github.com/timonv/rdispatcher). Dispatcher for Rust, broadcast and subscribe many to many.
* [rust-vim-setup](https://github.com/ivanceras/rust-vim-setup). Use VIM as your Rust IDE - set of bash scripts and a customised `vimrc` for Rust development.
* [Herd](https://github.com/imjacobclark/herd). An experimental HTTP load testing application written in Rust.

* A summary of the major changes to [Rust by example](http://rustbyexample.com/)
in the past few months include:
 - February 15, 2015: The [flow control section](http://rustbyexample.com/flow_control.html)
was [created](https://github.com/rust-lang/rust-by-example/pull/421) to house
all flow control operations together.
 - March 21, 2015: The [formatting section](http://rustbyexample.com/hello/print.html)
was [revised](https://github.com/rust-lang/rust-by-example/pull/496) so new
users are immediately confronted with the distinction of `Debug` and `Display`
and how to deal with them.
 - May 2, 2015: The table of contents was [reorganized](https://github.com/rust-lang/rust-by-example/pull/561)
so examples are sorted consistently by categories.
 - May 23, 2015: The [generics section](http://rustbyexample.com/generics.html) was
majorly [expanded](https://github.com/rust-lang/rust-by-example/pull/572).
 - June 15, 2015: The [closures section](http://rustbyexample.com/fn/closures.html) was
completely rewritten and [expanded](https://github.com/rust-lang/rust-by-example/pull/594).

# What's cooking on master?

XXX pull requests were [merged in the last week][merged].

[merged]: https://github.com/issues?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2015-06-15..2015-06-22

Now you can follow breaking changes *[as they happen][BitRust2]*!

[BitRust2]: http://killercup.github.io/bitrust/

# Breaking Changes



# Other Changes

* Thanks to Ashesh Kumar for pointing out that rust-lang.org was not
  configured with DMARC to prevent spoofing. The misconfiguration has
  now been corrected.

# New Contributors



# Approved RFCs



# Final Comment Period


# New RFCs


# Internals discussions

# Friend of the Tree

The Rust Team likes to occassionally recognize people who have made
outstanding contributions to The Rust Project, its ecosystem, and its
community. These people are 'friends of the tree'.

This week's friend of the tree was ...

# Crate of the Week

There are so many crates! It's easy to lose track of the good ones,
like [THING].

THING is a ...


# Upcoming Events

* [6/23. Hannover](http://blog.thoughtram.io/rust/2015/06/17/anouncing-hanovers-second-rust-meetup.html)
* [6/24. Columbus Rust Society](http://www.meetup.com/columbus-rs/)
* [6/29. Sydney](http://www.meetup.com/Rust-Sydney/events/222811456/)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Email [Erick Tryzelaar][erickt] or [Brian
Anderson][brson] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[erickt]: mailto:erick.tryzelaar@gmail.com
[brson]: mailto:banderson@mozilla.com

# Quote of the Week

*"Quote"*

Explanation and link.

Thanks to XXX for the tip. [Submit your quotes for next week!][submit].

[submit]: http://users.rust-lang.org/t/twir-quote-of-the-week/328
