# feed-me
Feed Me is a gadget for incorporating a Blogger blog feed on a Google Site.

This is my first attempt at a gadget!

The idea was borne of a few things coming together:
+ The desire to practice development
+ A new position at work
+ Attempting to get the most out of Google Sites, which is rather lack-luster
+ Wanting to include a basic Blogger feed on my Google Site
+ Google Sites limits the use of JavaScript and CSS, except in gadgets

So, apparently, there is no built-in way to incorporate a Blogger (or any) feed on Google Sites.  I tried a few gadgets that were listed, and none of them did what I needed.  They were either broken and forgotton, or they had funky formatting issues.  I stumbled across Google's Feed API, which has unfortunately been depricated, but I was determined to make my blogger posts seamlessly integrate on my site without the need of third-party apps and accounts, as the next phase would be to present teachers in my district with a simple tool to do the same, since we've gone Google in our district.

The first version is super basic and doesn't include everything I have planned.  I'm also learning how to use GitHub in this process, so bear with me!

2015-06-23
+ Added ModulePrefs
+ Added UserPref (does not yet make use of user selection of number of posts to show)
+ Added feed_gadget_test.html for viewing changes prior to inclusion in gadget or for direct embed into non-Google Site web page.

2015-06-19
+Initial version
