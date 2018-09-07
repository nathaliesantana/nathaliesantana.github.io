---
layout: post
title:      "**Cocktail Recipes CLI**"
date:       2018-09-07 04:34:16 +0000
permalink:  cocktail_recipes_cli
---


My first Flatiron School project was to build a Ruby Gem that provides a Command Line Interface (CLI) to an external data source. The external data source I choose was a list of classic cocktails that FoodAndWine.com reinvented to make them more up to date.

The CLI will scrape the webpage at the beginning of the interface, this will make the time the user spends in the application shorter from this point forward.

In the first face of the scraping, we will storage an object of each recipe. To each object will assign a name and url; from this url later we will scrape more information about the cocktail, like the ingredients and instructions.

Once we got the list of cocktails then we will proceed to scrape the url storage in the object and will grab the ingredients and instructions and will store them in the same object as well.

I think the biggest trouble I encounter creating my CLI was shaping the instructions string and ingredients array to a nice and simple visually agreeable text. It did take me a lot of time figuring out how to erase empty strings and new lines because some of the ruby methods I know didn't work well. However It did help me a lot because I got more use to look for information on the web, and not only on Flatiron; I read a lot and even if I didn't use the method I was reading  at that very moment, it did give me ideas on how to resolve other issues that presented me in the future. 

With this project, I changed my mind about iterators. I use to think it was this big block of code that always needed to be by its own, however learning to use these methods in one line of code, and being more comfortable in doing so, was great and not confusing at all, overall because it was what made my code looks how I wanted to. Bottom line, iterators are your friends use it wisely.

When I finished my CLI I pushed my gem to Rubygems.org, and it felt great! 
I can't wait for my next projects.

Cheers
