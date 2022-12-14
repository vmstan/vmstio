---
author: Michael Stanclift
title: Birdsite Bridges
date: '2022-12-29'
description: Ethical bridges from Twitter
tags:
  - twitter
  - defederation
---

Problem: Not all the people or organizations you follow may have migrated from Twitter to open social systems like Mastodon.

One option to follow such accounts are so-called "ethical bridges" from Twitter.
These are sites that connect to the Twitter API and create stub accounts for Twitter users, then mirror their content on the fediverse.

There are a few issues here:

- While some people may intend to follow the stub and understand the limitations, these accounts end up federated and searchable by anyone else in the instance, including on the federated timeline.
- They’re published without the original author's permission or consent.
- Although the bridge might work to make Twitter content visible, it can't create real conversation; your likes and replies with the person running the Twitter account are never seen by the author.
- In fact, there are a variety of backend issues when these stubs are followed, unfollowed, replied to, and so on, and their implementations don’t respond properly.
- These instances are typically overloaded or limited by Twitter API issues.

As such, we have actively been defederating (suspending) Twitter bridge sites, usually powered by a software package called Birdsite Live.
We will continue to defederate from such sites in the future, as we discover additional instances.
