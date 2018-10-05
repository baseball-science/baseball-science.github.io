---
layout: post
title:  "Pitch Selection"
date:   2018-10-05 10:30:06 -0400
categories: pitchfx baseball
---
The first question I want to try to answer is, "What pitch will be thrown next"?

This sounds like a pretty good first problem to start learning more about machine learning.

So to make this question more specific,

*Given a pitcher and batter, in a specific game situation, what is the probability distribution of the next pitch?*


## Gathering up data
The first thing we'll need is a bunch of data.  And the first place I'll look is towards
[Statcast](http://m.mlb.com/glossary/statcast).  Statcast, for those who don't know,
is a tracking technology that MLB installed in all their fields to allow for the
collection of a massive amount of baseball data.

In order to access some of this trove of data is  [Baseball Savant](https://baseballsavant.mlb.com/statcast_search/).  You can use this site
to set some query parameters and download a csv of the data.
