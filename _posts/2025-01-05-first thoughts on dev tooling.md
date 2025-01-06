---
layout: post
title:  "first thoughts on dev tooling"
date:   2025-01-05 22:14:00 -0800
categories: dev
---
relevant xkcd:

[![](https://imgs.xkcd.com/comics/real_programmers.png)](https://xkcd.com/378)

# rationale
i don't have decades of experience in the industry yet, so my preferences for dev tooling tend away from tools that require you to learn an obscure variant of vimscript or prototype your own gui and more towards tools that are easy to learn and effective. now, as someone who doesn't have decades of experience yet, i have a suspicion that the tools that i *think* are easy to learn and effective are just **a.** familiar or **b.** easy to learn, and i'm not quite as good at deciding what's effective as i think.

but given the prevalence of reinvented wheels in this field i'm not too worried about that.

with that said, here's my take on what makes developer tooling good and bad, as well as what specific tooling i use and why.

## good dev tools
as i've already indicated, i feel the primary thing that makes a developer tool good is ease of learning and effectiveness, each of which are affected in turn by many other factors.

- a tool can be easy to learn to a developer who is used to using other tools with similar styles, like how so many tools and editors can use vim-style bindings, while simultaneously being incredibly counterintuitive to another developer who hasn't crossed paths with that tool's genre or style before.

- a tool is only effective if it is relevant, and that is doubly true when management decides that it's necessary.

here's my definitely definitive list of what makes a developer tool good.

### simplicity
a good dev tool is simple where it can be. you might say needless complexity is the forbidden fruit of software development; it's necessary, but not always, and only in the hand of a true expert is it wielded in proper amounts, or at least that's what it seems like. simplicity is king. i read a post somewhere once that said you can tell when you're reading code written by a master when it looks so simple that you could've written it, because it's *not* simple, and i think that applies in these cases.

a simple dev tool is an understandable and therefore *usable* one.

### applicability
a good dev tool can be effectively applied to the situation you're facing. this, of course, implies that it actually does something, which is why there are so many dev tools; every tool does what it's meant to do in its narrow field, though every one tries to be applicable to every field. a particularly egregious example of this is microsoft excel, which can:

1. hold spreadsheet information
2. do math and draw graphs
3. [train a neural network](https://www.youtube.com/watch?v=hBBOjCiFcuo&t=3877s)
4. run doom, probably
5. calculate all the business logic for a midsize trading firm (source: a reddit post somewhere)
6. [emulate a cpu](https://github.com/InkboxSoftware/excelCPU)
6. file your taxes
7. fix your marriage
8. [function as a standalone operating system](https://xkcd.com/1667)