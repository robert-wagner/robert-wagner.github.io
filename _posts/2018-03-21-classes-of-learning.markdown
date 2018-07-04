---
layout: post
title: Simplest ways to achieve AI Security Levels
date:   2018-03-21 18:00:00 -0500
categories: jekyll update
---

Recently, there has been an explosion of techniques for privacy preserving machine learning. These techinques can be stratified into a variety of threat levels, namely:

- Public Models and Public Data
- Private Models and Public Data
- Public Models and Private Data
- Private Models and Private Data

# Reducing security models to others

The simplest model for a deep learning system is to collect all of the training data in a data warehouse which also holds the model. This centralization allows for the use of parrallel algorithms however prevents a security risk as all the data is in one place to be stolen and is out of the hand of the users.

