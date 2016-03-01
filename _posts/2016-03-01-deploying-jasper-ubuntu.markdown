---
layout: post
title:  "Deploying Jasper on Ubuntu 15.04"
date:   2016-03-01 20:13:00 +0530
categories: deployment jasper VoiceRecognition Siri OpenSource
---

<b style="font-size:20pt">What is Jasper?</b><br><br>
<a href="https://jasperproject.github.io/">Jasper</a><i style="text-decoration:line-through"> Reports Server is a stand-alone and embeddable <a href="http://community.jaspersoft.com/download">reporting server</a></i> is an open source platform for developing voice control applications. For me, just another cool problem to solve. The platform was made to be deployed on a Raspberry pi, but a lot of people have tried deploying it on desktop linux distributions too. Standard Raspberry pi deployment details can be found <a href="https://jasperproject.github.io/documentation/installation/">here</a>.

A GitHub issue can be found <a href="https://github.com/jasperproject/jasper-client/issues/20">here</a>, it talks about various problems people have faced on deployment of Jasper on ubuntu. I am here just to give it another shot.<br><br>

<b style="font-size:20pt">Let's start!</b><br><br>
GitHub Project Link: <a href="https://github.com/jasperproject/jasper-client">https://github.com/jasperproject/jasper-client</a>

Focussing on the core components first. An idea has been provided in this <a href="https://github.com/jasperproject/jasper-client/blob/master/client/requirements.txt">requirements.txt file</a>. 

<br><br><br>
P.S.: I am still working on it, so if you are reading this post and it seems I am missing something / interpreted something wrong, feel free to drop me an email and we can solve this problem together! :D

<b>May be useful</b> (this part of my post basically lists further possible options to look at and analyze): <a href="https://github.com/jasperproject/jasper-client/wiki/Roadmap">Jasper Product Roadmap</a>