---
layout: post
title:      "Creating My Coffee Shop CLI"
date:       2019-01-20 21:14:00 +0000
permalink:  creating_my_coffee_shop_cli
---



In addition to lame attempts at making my app’s personality resemble a caffeine fueled version of Bender Rodriguez,  I had a blast scraping the Starbucks site with Nokogiri.
Let’s descend into just exactly what I mean, shall we?  Cool.

This being the first development project ever attempted in a local environment I learned a lot about a lot.  In fact, before talking about Nokogiri I’d like to at least try to convey how mind bogglingly educational it was just coercing my text editor to play nice with Git.  Anyway.... To the magic of the Nokogiri (鋸) Gem!

The bread and butter of my application lie in methods I didn’t even have to build  (which I’m learning is a super cool trend in programming).  Nokogiri has the ability to collect data from HTML documents and store it in an array of nested hashes.  From there creation of usable Ruby objects becomes possible via iteration over the data and creation of new objects using the details as attributes.

This was my super cool to-do list:

1. Inspect Starbucks.com
2. Unsheath Nokogiri, which means ‘fine-toothed saw’ in Japanese 
3. Utilize its built in .css and .href methods to grab data about coffees and pastries
4. Instantiate some Ruby objects with said data, and then BOOYA… 
5. Build a controller CLI class so that users can access to the newly instantiated objects’ attributes
6. Drink a beer cuz you win, baby.

![](https://i.pinimg.com/originals/c8/98/79/c898796c13dd4aa2eeb76c4bd18aa62f.png)


