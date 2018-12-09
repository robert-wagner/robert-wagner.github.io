---
layout: post
title:  "Tree Decompositions"
date:   2018-12-07 19:41:03 -0500
categories: Graph Theory treewidth
---
Recently I have been spending a good bit of time working on graph theory problems. This post attempts to explain things which I found hard to grasp orginally.
# Algorithms on trees
Trees are very nice to deal with agorithmically since they have very constrained properties. Furthermore, every tree can be thought of as the joining of subtrees togther. This means that if we have a way to combine solutions to problems on subtrees to get the solution to the problem on the main tree, we can potentially speed up algorithms on trees using dynamic programming.

One example of an algorithm that runs 

