---
layout: post
title: "Knight's Tour"
date: 2012-11-20 14:47
comments: true
tags: [Kinght's Tour, Chess, Visualization] 
---
[Knight's tour](http://en.wikipedia.org/wiki/Knight's_tour) is a sequence of moves a knight makes  on a chessboard such that it visits every cell exactly once.

Here I'll be using [Warnsdorff's Rule](http://en.wikipedia.org/wiki/Knight's_tour#Warnsdorff.27s_rule) to find out a single tour considering every cell in a 8x8 Chess board as a starting point, one by one.

Simply put, Warnsdorff's Rule is a heuristic method which states that a Knight should always visit a cell that has maximum number of unvisited neighbours. A quick and dirty implementation can be found at <a href="https://gist.github.com/4116931">https://gist.github.com/4116931</a>.

Here's my attempt at visualizing the tour using [HTML5 Canvas](https://developer.mozilla.org/en-US/docs/HTML/Canvas): [http://arnavroy.github.com/knight-tour-visualization/](http://arnavroy.github.com/knight-tour-visualization/). Do give it a try!


