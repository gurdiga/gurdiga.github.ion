---
layout: post
title: My side project
date: '2014-04-04T10:57:00+03:00'
---

After last night’s “JavaScript MVC Frameworks” meeting I was super excited, in a way¹. As a result I woke up at 3 in the morning and went to my stand-up² table in the kitchen and started to tackle the app-sleeping issue with my free one-dyno xo-scripts app at Heroku that was supposed to do some daily data pluck-and-store, and for some reason didn’t in the last month or so. Got it working and added a reminder to my GCanlendar to periodically verify it works and a plan-B³ in case this doesn’t work in the long term.

¹ although the presentations were so-so, the event in itself was kind of exiting
² my laptop on top of a stool, on top of the kitchen table
³ just cron a curl on my Tonido

That script is a part of my side project. A project that I’m working on for 2 years in my spare time, and which got to the point where this morning felt like yet another failure. It’s an idea of a friend of mine Donciu: a productivity app for bailiff. It started quickly as a on-page app, build with jQuery and using nicely organized flat JSON files for storage.
After about a year of work I got it to “something” that was clickable, something that I could add users to, store documents, and print reports, and doing useful calculations. Something that looked like 75% of what we thought it should be at that time. We got to a place where we realized we didn’t imagine the UI quite right for the real-life process that we’re trying to facilitate and automate.

(One important thing in this story is that my friend was really hopeful about the success of this app, and because he is still to get his lawyer certificate in 6 months, meaning that now he’s unemployed, and he really needs it.)
At that point I realized that my jQuery soup that I have put together just does’t cut it any more: I can’t make the changes we needed without everything falling on me. The test suite that I brought about after half of that work was done, was pretty fragile, most of it was functional tests emulating the real user clicking through, and just a tiny bit of unit tests. About 6 months ago I realized that I can’t go any further like that, and I just stopped and said to myself that I just don’t know how to go about it. I need to learn some of this fancy, higher-level “architecture” stuff that was floating around, that I never gave a chance. I needed a way to make the code comprehensible as a system for someone new, which could very well be me after a few weeks of not looking on it. I needed a way to make it manageable.

The answer came from Robert C. Martin’s Software craftsmanship movement. I found a bunch of the Clean Coders vide series on torrents, then bought the other part of them, and I think I’m getting it enough to start that side-project afresh, which I did about a month ago. I’m still learning as I go.

This morning looking back at all this, I got a bit depressed and was determined to just back off from this, just admit to my friend that I’m not capable of getting done a project of this size and complexity. I’m just not good enough. Let’s face it.

A few of the last times we met he asked me how long is it going to take to finish it and I just couldn’t say anything about it. I have no idea. I seem just not to be able of estimating it. I think it’s because I don’t usually estimate tasks. And it’s even harder now, when I’m trying this new approach called “clean architecture” and I’m not done with user registration for this first month. I can’t see any way for me to estimate this project. I just don’t know how to go about it.

I also understand it’s tough for my friend to just wait. Before, in the “jQuery soup” version I was for a while steadily getting new features implemented: and it felt good for both of us. And now, from the user perspective, there is hardly anything moving. I understand this is hard for my friend and I feel uneasy about it.

At 5 o’clock in the morning I was determine to give up and just tell my friend to look for someone better.

On my way to work, I’ve read the “Breakable toys” in Apprenticeship Patterns, and how side projects a a great way to get better as a developer. It didn’t really change anything for my side project, but it gave me a reason to see it as something good, and continue working on it.
