---
layout: post
title: How to create a keyboard shortcut using JavaScript	
date: 2016-01-20
categories: tips-tricks
author: Andre Christoga
---

First of all, I accidently know how to create a keyboard shortcut in javascript because of an experiment project (ulan) with my friend, [@vickydasta](http://vickydasta.github.io) <br>

## Keymaster
Keymaster is the simplest way to create a keyboard shortcut in JavaScript, I'm using it for `ulan` <br>
CDN : [https://cdnjs.cloudflare.com/ajax/libs/keymaster/1.6.1/keymaster.min.js](https://cdnjs.cloudflare.com/ajax/libs/keymaster/1.6.1/keymaster.min.js)

## How it works
How does it works? <br>
When the person press "/", they will be linked to another page/website

### The Code
The key we will be using is "/", and when their press it, theyre linked to a new page/web <br>

```
key('/', function(){ 
	window.location.href = 'chat.html' 
});
```

I will describe the code below: <br>

`key('/')` : "/" Shortcut <br>
`function()` : The keyboard shortcut action <br>
`window.location.href = 'chat.html'`: Linked users to chat.html

The live demo is available at [codepen]()

### Referency
[https://github.com/madrobby/keymaster](https://github.com/madrobby/keymaster)