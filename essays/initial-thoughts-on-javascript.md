---
layout: essay
type: essay
title: Initial Thoughts on JavaScript
date: 2017-09-01
labels:
  - JavaScript
---

My first impression of JavaScript was not a good one. Redditors (outside of /r/javascript) can sometimes paint JavaScript in a bad light, noting how the language is full of dangerous pitfalls and how if you aren't an expert, your projects will quickly and surely descend in to madness. Some particular snippets of JavaScript code that can confound anyone who doesn't use it (i.e., me at the time) are the following:

```javascript
> null > 0
false
> null >= 0
true
> null == 0
false
> null <= 0
true
> null < 0
false
```
```javascript
> '5' - 3
2
> '5' + 3
'53'
> '5' - '4'
1
> 'foo' + + 'foo'
'fooNaN'
> '5' + - + - - + - - + + - + - + - + - - - '-2'
'52'
``` 

## Seeing the light!

Before I began to learn about JavaScript, I had some exposure to Python and Scheme. Python was not too bad getting used to coming from an OOP background. The strangest things to me were dynamic typing and heterogeneous arrays. Scheme however forced me to learn about and *understand* foreign concepts such as functions as first-class citizens, closures, and first-class continuations.

Being aware of concepts from Python and Scheme prior to learning about JavaScript has made the act so much more interesting. So far my impression of JavaScript is entirely positive. It seems like a very powerful language due to its history and market prevalence. I think that the language has a lot packed in to it, and there is a lot of synergy in learning about JavaScript along with Scheme and Python.

## About athletic software engineering

I really enjoy the approach taken in ICS 314. I wish other programming courses employed the same teaching methods. Being forced to complete unknown problems under time constraints almost daily is something that I will need to become accustomed to. The method definitely works for me. The only thing that would hold me back is old procrastination habits, which I am in the process of breaking. There is just something about this semester that gives me a lot of motivation.
