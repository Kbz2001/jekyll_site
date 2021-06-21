---
layout: single
title:  "Discord Rich Presence Project"
date:   2021-05-18 15:21:48 -0500
---

The first project I will talk about is a Discord rich presence application. For those unfamiliar with Discord, it is a
social media application that allows you to communicate with other people. It is most similar to Skype except it is a lot
more customizable. One feature that Discord has is that if you allow it to, Discord will detect what application is currently
open on your computer and will display it under your account so other people know what you are currently doing. This opens
up many opportunities for developers as they can create their own custom displays for specific applications. 

I had the idea of creating a rich presence for Google Chrome because I noticed that Discord had very low support for Google 
Chrome. Through research online I noticed that I wasn't the first one to come up with a similar idea. All the existing ones 
didn't have what I wanted. I decided that instead of reinventing the wheel I would use the existing projects as reference
and then add the features that I wanted. 

Many of the existing projects detected if Google Chrome was open, however I wanted something more specific. I modified my
version to further detected which websites were open. I added detection support for popular websites such as YouTube,
Google Docs, Google Sheets, Google Drive, Google Slides, GitHub, and as a default if the user is on a website that I didn't
add support for it simply displays Google Chrome.

Examples of this application in use are below:

<div>

<img src="{{site.url}}/jekyll_site/assets/images/ChromeRP.png" width="315" alt="socials2" />

<img src="{{site.url}}/jekyll_site/assets/images/GoogleDocsRP.png" width="312" alt="socials3" />

<img src="{{site.url}}/jekyll_site/assets/images/GitHubRP.png" width="306" alt="socials4" />

<img src="{{site.url}}/jekyll_site/assets/images/YoutubeRP.png" width="315" alt="socials5" />

</div>