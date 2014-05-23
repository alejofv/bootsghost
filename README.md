bootsghost
==========

A minimal Ghost theme using Bootstrap

_Disclaimer_: I'm a developer, not a designer :)

This is a minimal theme I made for my personal blog ([here](http://alexphibits.azurewebsites.net)). I was looking for a simple responsive design, displaying just the blog name with a few links and the posts titles.

* It uses Bootstrap and Hightlight.js CDNs.
* Support for static pages (`page.hbs`included)
* Includes `rel=author` link in posts
* Disqus comments
* Google Analytics

**Customization:**

* You can switch to a different Bootstrap or Hightlight.js theme changing the linked css in `default.hbs`
* The static links at the left-side are in `partials/static-links.hbs` 
* The social links (icons) below the author info are in `partials/social-links.hbs` 
* For Disqus and Google Analytics, change the related variables in `default.hbs`. Look for the `Disqus params` and `Google Analytics params` comments.