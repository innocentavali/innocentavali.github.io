---
layout: post
title: How to scrape popcorn pictures from a website
key: 20180716
tags: 
  - Python
---
## Before making fun

Since I learned some stuff about machine learning, I always want to make use of it and create something fun.

For example, I want to build web applications which can automatically process images. But where can I get the material? 

I don't like the images from some open dataset. It's just...too old...and ugly! 

And sometimes it's also hard to find the specifc component I want. 

So I decided to scrape images from the website myself! Afterwards, I can do whatever I want~ 

## Let's get some popcorns

First let's go to one of my favourite websites with quality pictures - Pinterest.

![Popcorn](/image/Pinterest1.png){:width="800px" height="504px"}

After typing in 'Popcorn', boom! I'm already hungry. But let's finish the job before I run into a store.

Here let me introduce a trick: Select any content you are interested in on the website, click your right mouse and choose "inspect".Then you'll see all the elements in the html format. Place your mouse on any line, it'll automatically locate the element. This is the easiest way to help you find out, in the raw html file, how your content is coded! 

![Inspect](/image/Pinterest2.png){:width="800px" height="500px"}