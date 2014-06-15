# U1.W2: Chrome Dev Tools Challenge Reflection

* Describe the Document Object Model? What about it makes sense to you? What doesn't? What seems good and bad about it?

	* The Document Object Model is a way of organizing webpage objects into a tree-like structure, where each object has a single parent object and can have multiple child objects.  The DOM is essentially a map of a webpage and all of its elements, which enables a developer to integrate JavaScript into the website to create the effects and dynamic nature of web applications.

* How did using Chrome Web Tools to look at your site and a wordpress.com site compare?

	* To do this comparison, I created a blog on wordpress.com and made one post.  I figured it would be interesting to see what the HTML and CSS looked like withouth making many entries - essentially keeping it as simple as possible, so that it would be a better comparison to the simple blog I created myself.  I'm actually not very sure if adding a lot of entries to a wordpress blog changes much of the HTML and CSS, though.

	* Anyway, what I noticed immediately was the differential in volume of code.  My blog was limited to a few lines (without drilling into them): a head, body, and a list.. that's pretty much it.  There were significantly more lines upon first opening the wordpress blog, many of which were 'script' elements, which I hadn't used myself.  My next comparison was on the Network tab.  My blog had a total of 3 objects listed in the network tab.  I counted upwards of 30 on the wordpress blog, many of which were javascript objects or additional stylesheets.  I only used one stylesheet, and no javascript.  My last comparison was to analyze both sites with PageSpeed.  Wordpress scored a 69 on speed and 99 on UX, vs my sites 66 and 89 (ok, not so bad!).  All of google's suggested changes to my site were tagged as low priority, vs. wordpress's that had a range from Low to High.

* Did you find Chrome Web Tools fun, helpful, or a pain to work with?

	* I really really really really like chrome web tools.  It's going to come in handy so often.  I'm really looking forward to editing my blog directly in the browser, exporting the new html and css files, and then loading them to my github repository.  It was also AWESOME being able to see some of the html and css code for a lot of cool sites.  I definitely took some good ideas away from a couple really nice looking sites.

* Did you have an "aha" moments or were any concepts solidified?

	* It was great seeing how a couple sites wrote the positioning of their HTML elements.  There were a couple moments where I was like "ohhhh that would be a much better way of doing that!".  So, hopefully through more analysis of a couple websites, I'll be able to clean up the code I used for my blog and make things a bit more efficient / clean.

* Did you find any resources on your own that helped you better understand a topic? If so, please list it.

	* Andrew McClellan posted a link to the August Suns google plus page that was really helpful in understanding the DOM better:  https://www.youtube.com/watch?v=-0ZcldkGlt8.  Honestly, the first resource in the lesson, the one on the mozilla developer site, I found to be really confusing.  The skill crush one was much better at dumbing the concept down for me.