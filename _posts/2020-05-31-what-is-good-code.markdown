---
layout: single
title:  "The Clean Code Fallacy"
date:   2020-05-21 11:38:25 +0200
categories: programming programming-philosophy opinion
header:
  overlay_image: /assets/images/All_Gizah_Pyramids.jpg

---

Discussions about clean code usually miss the point.

As developers, when we talk about clean or good code we often get caught up in the details.

We think about design patterns, [single responsibility](https://en.wikipedia.org/wiki/Single-responsibility_principle), [dry](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) and so on and so on.

These discussions are important but they make it easy to loose sight of what is really important:

Good code does what it's supposed to do.

"Well duh!" you might be thinking right now. It is so obvious. And clearly there is more to the story.

The "does what it's supposed to do" part usually includes some implicit sub goals which are not specified in the definition the product team hands you.

Unless you are writing a prototype that will be thrown away afterwards (though somehow those always end up in production) those sub goals include extensibility and reliability which usually entails readability and testability. And clearly you also should not waste too much development time on it.

In the startups I've worked in so far, time now is usually being valued much higher than time later.

And after aaaaall that, we can finally begin to even think about design patterns, about our precious scalable architectures and if we should put comments in front of our functions or if they are self explanatory.

But when we talk about them we should not forget that they are means to an end and not the goal.
