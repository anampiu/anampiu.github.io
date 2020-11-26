---
layout: post
title: Building blocks.
---

Hold on to your trousers, today I plan on being a little pedantic, but in retrospect...what is programming if not codes with an overload of pedantry.

Websites of this age have a couple of items tied to them. Typically, you would have your HTML pages, CSS files and javascript files. I assume you are conversant with what each of these are, but since we are being meticulous:

HTML - This is where your content goes, mainly text and images.
CSS - This files style your content, give it color and beauty.
Javascript(which has no relation to the JAVA programming language) - This gives your content some behavior and makes it dynamic, it sort of brings your site to life, if you could say so.

Back to my point, there is a convention folder and file structure that each website should adhere to so that referencing is easy and it is understandable to other developers.

I'll make it a little visual for you

```
        index.html
        about.html
        *css>style.css
        *js>style.js
        *img>img1.jpg
             img2.jpg
             img3.jpg
             
        * denotes a directory
```
We have the parent folder that has the html files, the CSS, Javascript and images folders. Then each folder has the type of files that its name states. This might change, mainly in the case of a web app but we'll get there young padawan.

I recommend you have a skeleton file structure somewhere in your computer which you just yank out every time you have a new html project. It might save you time. 

#### Challenge:
A good example to look at would be [this repository on github](https://github.com/tamzi/Yolby). Clone it and have a good look at it. 
After that, try and make your own with working links and a skeleton index.html. Aren't rules meant to broken, so if you come up with a file structure that throws the one in business out of the water, please, spread the word!