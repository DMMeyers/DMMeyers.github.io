---
layout: post
title: Plushy Redux
subtitle: My Digital LEDs
tags: [HW]
comments: true
---
# This Project...

Was a continuation of the good circuitry work we did with mr.plushy, except now our task was to translate how the circuit works into code. Essentially, the diodes will only emit light when variables switch and button are set to 1, which we determined to be "on". If either of them was anything except for 1, then the lights will be off and the circuit is open.

Here is an example of the output when the switch and button are both set to 1

![Output of code that reads "ON ON ON"](https://DMMeyers.github.io/assets/pproto.jpeg){: .mx-auto.d-block :}


### The advice I would give my past self is to think about each led specifically. My first iteration was very simple and, while it worked (sorta), I was unabble to check the values of each LED. Additionally, in the student help hours I learned that the code would be more efficient if I did not nest if/else statements, which was a surprise to me, as I had assumed that this new technique would always be the more efficient road. 
