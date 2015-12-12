---
layout: post
title:  "Responsive Shopping Challenge - Bloc"
date:   2015-12-09 13:46:24 -0500
categories: bloc
---
Looking Back at a Responsive Shopping Site

Conception and Development

The challenge was straightforward enough - create a responsive shopping site. I knew I wanted to create something that didn't already exist. I looked at a several pumpkin seed/produce delivery websites to get a feel for the overall process of produce purchasing and delivery. I envisioned the user being working parents (or busy people) who wanted to carve and display some pumpkins for the fall holiday season, yet didn't have time to buy them. I wanted to offer a curated selection of specialty pumpkins for the discerning buyer. I found and chose my selection using images from a seed distributor, and played around with layouts until I found a group of pumpkins that appeared both family-friendly and upscale.

Wireframes and Prototypes and a few Design Decisions

I used Balsamiq for a few pages, to get the general feel and layout fixed before I began prototyping in Sketch. I knew I didn't want a left navigation bar that collapses - because a hamburger menu is not necessarily a navigational design solution on a small screen. A better fit in this case seemed to be dividing the pumpkins by size and color, with a top menu dropdown.

I developed a color scheme, which very quickly seemed way to dark, so with some input from @nikibrown and @stevenpclark, I lightened up my primary color (love you sass) and used the color as div backgrounds to anchor the main navigational bars and background cards.

As I started coding, I got very overwhelmed with all the different elements I had planned and designed for the site - but @nikibrown gave me great advice - to just think of each segment of the page as a piece, and work through each piece. As I worked, I kept track of the different development pieces I needed to work through and solve with trello and it helped my keep my workflow moving, instead of getting distracted as some things broke while working on this other thing.

I used Foundation 5 as a grid system. It seemed to have less bloat than Bootstrap in this case, and it was a different system than Skeleton, which I used and really enjoyed in earlier projects. It took one complete restart of this project (which now I realize wasn't necessary, 20/20 hindsight!) to get Foundation working for me, but it was helpful to use something a bit more robust than Skeleton to get the responsiveness exactly how I wanted it (small/medium/large/etc. columns).

My Favorite Part(s) of Development

On the checkout page, there is a button: "Remember Me?" it implores the user. It makes a div appear with the password information. In the whole site, this tiny little feature, with about a half hour of javascript research and some jquery, was the most fun. I loved getting it to work. It's not the fanciest, I wish there was a nice fade or transition or css animation to smooth the hide/show, but it works.

I also loved understanding how and using the angle mixin for the headers. Before I began bloc I noticed a few sites using them and thought they were snazzy. I loved having the opportunity to use it in this site.

Learning from Pumpkin Patch

I really didn't want to work on this project, though I am pretty proud of how it looked when I finally stopped. This project was challenging, in that I got a chance to work on something much bigger than just a landing page. Using the same sass files over the whole site made it much easier to develop and maintain a consistent look and feel for the site, and more straightforward to make small changes to impact the whole document when necessary.
