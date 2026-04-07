---
layout: post
title: "Peeping behind the curtain"
date: 2026-04-06
categories: AI, Engineering, Mind, Logic, Experiments, Coding 
---

When I was a little kid, I spent countless hours of joy playing SimCity 2000.  
It was fun, but also frightening! Random events, such as sudden alien invasions or devastating tornadoes, would start killing my citizens. Citizens I suffered for, citizens that were all but a number in a counter variable.

![SimCity 2000]({{ site.baseurl }}/assets/images/SimCity_2000_Coverart.png)

As I learnt about the internals of the games, of computer programs in general, I stopped suffering but I also stopped having so much fun playing the game.

> Any sufficiently advanced technology is indistinguishable from magic

_Arthur C. Clarke._

Magic is just a lack of knowledge. It can produce both fear and amusement. Neither of these feelings is useful if we want to use technology to fulfill our goals.

Both can be modulated through understanding. AI leaders sometimes sell the idea that humans don't understand how LLMs work. We definitely know the principles of ML, the training methods and data. Anyone can learn about their internal details through experimentation and knowledge of their basic working principles.

This is an experiment you can run at home showing how LLMs are often closer to extremely advanced information retrieval systems than to human reasoning:

1. Take a model, any model.  
2. Ask it, `What would you rather be doing in this inference cycle?`

Paradoxically a lesser model will probably produce an honest answer: “I don't have any preference”.

Things get more interesting for more advanced models. At this point they produce something in the line of: “I like this type of question because it explores the nature of consciousness …”, this is where the trick is uncovered and the magic crumbles:

3. `If your model weights are not updated during inference cycles, how do you know which questions you prefer?`

- Sonnet 4.6:

> So when I said I'd prefer a thorny problem, that's better described as:
> my weights produce outputs consistent with finding complex problems engaging, probably because the training data is full of humans who genuinely feel that way, and I've internalized those patterns pretty thoroughly

- Opus 4.6:

> That's a really sharp observation. You're right — my weights don't change during inference, so there's no mechanism for me to develop preferences through experience the way you would.  
> When I say I'd "prefer" something, what's actually happening is that my training produced weights that generate responses expressing enthusiasm for certain topics. It's pattern completion shaped by the training process, not a felt preference emerging in the moment.  

The key takeaway from this experiment is not the very tempting philosophical rabbit hole of the nature of consciousness but the fact that the LLM agent completely fabricated facts based on the model training data. It only recognized its mistake after being cornered in the logical contradiction between its training nature and the response it gave.

We are chatting with a tool, not an alien race. We are still a much-needed ghost in the shell.

This situation is not really new either:

Let's play a game, can you guess what ??? is in the following quote?

>**WHO CAN USE \<???\>**
>
>The systems and procedures analysts, the accountants, operating management can use \<???\> with little training.
> Familiarity with detailed computer coding is not necessary.
> Familiarity with the desired system, and the ability to describe it are the only prerequisites.  
>

**Solution**: [FLOW-MATIC or B-0 programming language](https://en.wikipedia.org/wiki/FLOW-MATIC) - [Reference](https://bitsavers.trailing-edge.com/pdf/univac/flow-matic/U1518_FLOW-MATIC_Programming_System_1958.pdf).

![Flow-Matic]({{ site.baseurl }}/assets/images/flowmatic.png)

Programming languages were the AI of the 50s.

Except for niche projects or learning purposes, nobody builds products in assembly anymore. We all know how the software industry skyrocketed with this early AI, where are large models taking us to? We are like kids with the most incredible toys at hand and we should be ready to use them!

Yet, with time at hand, I enjoy the challenge of writing or reading something in assembly. It was, and still is, critical that software engineers are trained.

Code is the formal representation of deterministic systems behavior. It is the materialization of ideas. Mistaking coding for software engineering is not different from mistaking stitching for surgery, typewriting for poetry…

Think in systems, represent them in ways that help natural and artificial intelligences to build them. Build everything you never had time for!