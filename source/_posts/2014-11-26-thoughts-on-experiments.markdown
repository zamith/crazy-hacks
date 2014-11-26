---
layout: post
title: "Thoughts on trying new things"
date: 2014-11-26 12:12
comments: true
categories: [ruby]
---

TL;DR Trying new things is fun. Do it more often.

Everyone has a lot of ideas for new stuff, as developers we are blessed to be
able to bring some of these ideas to life. More often than not, though, we aim
too high and quit before we even get started because of how daunting a task it
might be. Other times we are doing so much at work already, that we just want a
break.

In any of the cases trying new things will do you good. Try a new language or
technology that excites you. You'll learn new things that can be used in your
daily job, or at least have fun. If teaching is your thing, there's also the
benefit of learning how to be a newbie again, which gives you perspective.

## Starting something

Starting something is the hardest part, I always fear that I get too invested in
a project that ends up to be a piece of crap. Turns out that a lot of times it's
when you don't care if it is crap or not that the best things come into
existence. There's is an entire conference dedicated to instigate the Ruby
community to build more strange things, because some of them will be great. It's
called [Keep Ruby Weird](http://keeprubyweird.com/), check it out.

A good way to start creating things is to think of what you do all day and try
to automate (partly or completely) a small part of it. It's likely that your
problems will be shared by other people around the world, or at least your
coworkers.

I did that and created something called [**Github Nice Guy**](https://github.com/zamith/github-nice-guy).

## Github Nice Guy

The problem I decided to tackle was the fact that pull requests are forgotten.
This can happen because you lost interest in the project, the project is
deprecated or relocated, etc...

My idea to solve this is described in the README as:

> Github Nice Guy is a small Ruby script that fetches the open pull requests for
> a given user (or organization) and sends a weekly friendly reminder with links
> to them to whoever you think should know about it.

The coolest thing about this project, in my opinion, is that it took less than
30 minutes to get done (the first version at least). This is not because I'm an
awesome developer or have mad typing skills, it's mostly because it was just a
couple of gems put together in a very shady way that kind of worked most of the
times. But I learnt new things about the Github API (and how awesome it is),
sending mails from a ruby script and integrating ruby scripts with [whenever](https://github.com/javan/whenever).

There's nothing really fancy about it, but I got to try new things without a lot
of commitment, and as a bonus got a small service that is now running in my
company.

## Conclusion and stuff

The main thing to get from this post (if there is one) is that you should see
the resulting "product" as a bonus, the path to get there is what really counts.

This path can be miles long or inches short, that's up to you, but building
something that helps you out on what you do everyday is a good way to start
gaining momentum.


