---
author: Kushal
layout: post
type: post
date: 2015-03-11 17:55
title: "Security on Cloud"
category: fedora,dev
tags: [cloud,security]
---

My recently deployed public cloud on DigitalOcean started having hacking attempts. The starnge fact is that in a matter of 6 hours of its commission and assigning a domain, I had 360 unsuccessful login attempts over SSH.

For the moment I have restricted access over the 22 port and enabled some SElinux policies.

The dev machine is running a Fedora 21 instance and would be primarily used formy fedora testing and development. 

Next up : * Security fixes for my cloud
	  * Setting up Amazon EC2 instance
