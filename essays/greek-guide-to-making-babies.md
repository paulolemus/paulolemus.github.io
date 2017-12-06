---
layout: essay
type: essay
title: Greek Guide to Making Babies
date: 2017-12-05
labels:
  - Design Patterns
  - Composite
  - MVC
---

<img class="ui medium image" src="https://cdn.ancienthistorylists.com/wp-content/uploads/2015/03/prometheus_greek_god.x34319.jpg"/>

# It is time to punish man and their champion Prometheus

You are the almighty Zeus! No one crosses you, especially Prometheus! He just tricked you into accepting a sacrifice of literally just bones from man as your share for all of eternity. It's about time to show both Prometheus and man who **The Man** is. It is time to make a mortal.

This mortal shan't be made the traditional way however with the birds and the bees method. No no no, this mortal shall be hand crafted especially to play a prominent weakness of man: a weakness to stunning beauty.

We shall make Pandora! How oh how can we build this finely tuned deception? It looks like as Zeus, it is high time to gather a small subset of the Gods to form something with more production power than even Hephaestus has: an Agile development team. You as Zeus take the role of the almighty Scrum master and your team gets to work.

Pandora is made up of several complex parts. You as Zeus recognize that Pandora is pretty much a **composition** of most importantly the following items: body, deceptive heart, lying tongue, forbidden jar, gifts of wealth. Your Agile team takes takes on the following tasks to develop each of these *classes*. Hephaestus develops the body out of molded earth, Hermes gives develops the deceptive heart and lying tongue, Athena the gifts of wealth, and you develop the forbidden jar (these statements may not be verified). Finally, Pandora as envisioned by you is instantiated by the composition of these separate classes. You chose to follow this design pattern of composition to ease the creation of Pandora because it just makes sense. It allowed you and your team of Agile developers (gods) to separately develop and test everything that makes up Pandora to perfection before actually putting them together. I forgot to mention that of course Pandora *is* a human so she inherits from humanity, however here the composition is what makes Pandora so awesome. You can't wait to see the damage Pandora causes to man once her jar has been opened.

Oh yeah, and you also chained Prometheus to a rock and got an eagle to eat his regenerating liver out of him every day.

# Zeus's unintended gift to man

"Wow what a fantastic design pattern!" said all the mortals of the world when the Pandora was bestowed upon us. The mortals then copied this design pattern and it passed down through the ages until it reached me, a lowly mortal, and helped me develop a class to model a Syntax Rules macro in the Scheme language, that is composed of several Syntax Case instances.

For example, we have
```
; A macro
(define-syntax my-or
  (syntax-rules ()
    [(my-or) #f]       ; A syntax case
    [(my-or e) e]      ; Another syntax case
    [(my-or e1 e2 ...) ; Yet another syntax case
     (let ((temp e1))
       (if temp temp (my-or e2 ...)))]))
```
A `SyntaxRules` macro such as this my-or macro could be composed of three `SyntaxCase` instances, where each `SyntaxCase` can match and expand a single pattern / template case.

