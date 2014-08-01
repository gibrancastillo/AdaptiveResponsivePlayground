AdaptiveResponsivePlayground
============================

Adaptive Responsive Web Design:  Only  those elements deemed appropriate exist on each experience.  Offers better performance on bandwidth-constrained devices.

Adaptive-Responsive Design is about creating one design and code base capable of delivering the best user experience across all channels:  Omni channel [mobile, tablet, laptop/desktop, hotspots, store display, billboards, etc.]

Adaptive:  adapts to specific situations/surroundings; in other words, how much data gets sent back from the model to the view depends on the form factor or screen size.

Responsive:  to display optimally on different screens; in other words, how/where/ what widgets get display on the view depending on the form factor or screen size.  

Good performance = good design yield UX.  +100ms = -1% Amazon sales.  User expects to wait for 2 seconds, after 3 seconds 40% will abandon your site.  75% of shoppers who experience an issue will not buy from that site and go to a competitors site.  http://www.webpagetest.org

Number of request and Bytes downloaded determine the performance of your site [given everything is working properly].  

Biggest Wins for requests
1. Image formatting, size and spriting
PNG (Portable Network Graphics):  for transparency (PNG-24:  Prettier transparency, tons more colors, larger file size), or there are few colors (PNG-8:  Max 256 colors, uses alpha transparency, generally smaller file size).
JPG or JPEG (Joint Photographic Experts Group):  for photos and other images with tons and colors.  No transparency.
GIF (Graphics Interchange Format):  They're very heavy, and most animations can be replaced with CSS3.
Use tools that best Compress/Optimize for PNG, JPEG and GIF.
CSS3 Gradients can handle transparency, can be overlaid on a background color, Eliminate an image request


2. Cutting down fonts weights
IE-8 downloads ALL THE FONTS even if they are not used on the page.  remove some of the characters to descrease file size.


3. Semantic markup and repurposability
HTML5 Semantic Elements offers new semantic elements to clearly define different parts of a web page:
<header>
<nav>
<section>
<article>
<aside>
<figure>
<figcaption>
<footer>
<details>
<summary>
<mark>
<time>


4. Deliberate asset loading (conditional loading)
Adaptive-Responsive Web Design - Mobile First
Adaptive:  Server-side detection on screen size  http://www.adaptive-images.com/
Responsive:  Client-side detection on screen size https://github.com/scottjehl/picturefill
Mobile performance is terrible; a device has to establish a radio channel before it can send/get data.





Memory Footprint Analysis
=========================
Memory Footprint is how much memory a program uses.  Important in constrained environments such as mobile devices.
Memory usage of an algorithm; determine the amount of storage required for each item.
Memory footprint of an implementation; understand how the underlying data structures might be implemented.
Example:  Unicode string, which enables more compact representations of strings while making it more expensive to perform many common string operations.
