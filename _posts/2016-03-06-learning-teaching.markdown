---
title:  "learning and teaching"
date:   2016-03-06 13:03:00
categories: [devops, teaching, learning]
tags: [devops, teaching, learning]
---

devopracy is a project for both learning and teaching DevOps. It can be difficult to experiment as an infrastructure engineer; commercial infrastructures are often vast and brittle, and management is unconcerned with experimentation. Consider the opportunity we have with the event cloud: it is a toy infrastructure, inherently portable, disposable, redundant, and modular. It is a perfect use case to try out a one-off deployment technique, or a piece of code out of scope of your regular infrastructure. We have a playground for high security cloud infrastructure, and you can use the code you contribute on internal projects as you like.  

Teach what you know, and make an issue for the technology you would like to learn. Provided it uses open source code and has some relation to the road map, the issues board can act as 'help wanted' for less experienced engineers. 

By the same token, senior engineers are encouraged to contribute through code review. We are using a full battery of style guides, linters, and test frameworks to try and build consistent, maintainable code. The choice of [Chef Zero](https://github.com/chef/chef-zero) as a provisioner has everything to do with the excellent support for infrastructure test through kitchen, foodcritic, and chef-spec. Other Ruby code has rspec and serverspec test coverage. Suggestions for testing and monitoring other parts of the cloud are appreciated; please document your ideas as issues. 
