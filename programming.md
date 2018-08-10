---
layout: single
title:  "MakeCode Pilot"
---

In all previous years, First Lego League has required that missions be programmed only using
the official EV3 Mindstorms app. This is good because it has created a level playing field among
teams and it ensures that teams don't get hung up on idiosyncracies (Ev3 is guaranteed to work across
platforms and doesn't require special programming knowledge).

However, as time has gone on and computer science education has moved younger in schools, the
flaws in the Mindstorms system have become more pronounced. There are a few major issues:

* It requires native software, and files are saved in nonstandard binary format, so it is difficult
for teams to share easily or collaborate. Other systems may have web sharing.

* EV3 is a custom programming environment that doesn't translate easily to more common programming
languages like JavaScript or Python that may be taught in school.

* More complex programs can be quite difficult to manage; for example, the only modularity is "My Blocks",
which suffer from an inability to nest (you can't call a My Block from within a My Block). Larger programs
have a sparse visual layout - a single if/then block can take up the whole screen. Modern languages
are more dense.

This past spring, our team experimented with a few different alternative programming languages, including:

* Python (via ev3dev)
* Open Roberta
* Microsoft MakeCode

Each of these has its own strengths and weaknesses. Ultimately, I think that MakeCode is a great
alternative to Mindstorms because it is compatible with JavaScript, more condensed in a web browser, and
has limited official support from LEGO (so it's unlikely to suffer as many weird bugs in critical conditions).
Open Roberta was way too flaky to use in production, and Python is probably too advanced for the age group
we are working with (without specialized training). Perhaps in future years we may introduce Python.

For this season, we are going to try out the MakeCode pilot and see how it turns out.
