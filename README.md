AdaptiveResponsivePlayground
============================

Adaptive Responsive Web Design:  Only  those elements deemed appropriate exist on each experience.  Offers better performance on bandwidth-constrained devices.

Adaptive-Responsive Design is about creating one design and code base capable of delivering the best user experience across all channels:  Omni channel [mobile, tablet, laptop/desktop, hotspots, store display, billboards, etc.]

Adaptive:  adapts to specific situations/surroundings; in other words, how much data gets sent back from the model to the view depends on the form factor or screen size.

Responsive:  to display optimally on different screens; in other words, how/where/ what widgets get display on the view depending on the form factor or screen size.  

Good performance = good design yield UX.  +100ms = -1% Amazon sales.  User expects to wait for 2 seconds, after 3 seconds 40% will abandon your site.  75% of shoppers who experience an issue will not buy from that site and go to a competitors site.  http://www.webpagetest.org

Number of request and Bytes downloaded determine the performance of your site [given everything is working properly].  

Biggest Wins for requests
1. Image formatting, size and spriting :: Responsive Images
PNG (Portable Network Graphics):  for transparency (PNG-24:  Prettier transparency, tons more colors, larger file size), or there are few colors (PNG-8:  Max 256 colors, uses alpha transparency, generally smaller file size).
JPG or JPEG (Joint Photographic Experts Group):  for photos and other images with tons and colors.  No transparency.
GIF (Graphics Interchange Format):  They're very heavy, and most animations can be replaced with CSS3.
Use tools that best Compress/Optimize for PNG, JPEG and GIF.
CSS3 Gradients can handle transparency, can be overlaid on a background color, Eliminate an image request


2. Cutting down fonts weights :: Responsive Fonts
IE-8 downloads ALL THE FONTS even if they are not used on the page.  remove some of the characters to descrease file size.


3. Semantic markup and repurposability :: Responsive Navigation
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


Responsive Tipography:  Root EM - size of the font is relative to the root's font size, not the parent, as with the EM unit.

Responsive Videos:  Embed an HTML5 video in your page and make it responsive.  The <video> tag easily supports using a percent width.

Responsive Layouts:  Floating elements that cannot fit into the width of their parent stack horizontally.

Responsive Padding:  The total width an object takes is its own width plus the width of both sides of its padding, its border, plus its margin, on both sides.
Formula:  2 x (margin + border + padding) + content = total width
Percent padding:  static padding / total width

Example
For an image that is 200px wide in its normal non-responsive state, your typical padding may be 8px, therefore using the previous box model, the formula can be framed as follows:  2 x (0 + 0 + 8px) + 200px = 216px
percent padding:  8px / 216px = 0.037 rounded to 4%



Memory Footprint Analysis
=========================
Memory Footprint is how much memory a program uses.  Important in constrained environments such as mobile devices.
Memory usage of an algorithm; determine the amount of storage required for each item.
Memory footprint of an implementation; understand how the underlying data structures might be implemented.
Example:  Unicode string, which enables more compact representations of strings while making it more expensive to perform many common string operations.
