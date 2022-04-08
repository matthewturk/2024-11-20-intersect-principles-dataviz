<!-- .slide: class="titleslide" -->

# Web Presence Beyond the Basics

## Matthew Turk

<p data-markdown=true><tt>mjturk@illinois.edu</tt></p>

---

## Thank you

I'm happy to get to share this with you!

<div class="fragment">And before I get too far in, let me encourage you to <i>interrupt</i> with questions, disagreements, and spontaneous applause.</div>

---

## The Basics

For professional purposes you should have a web presence.  You have several choices:

<ul>
<li class="fragment"><b>MySpace</b>: this is not just for bands!  You can have one even if you don't play music.</li>
<li class="fragment"><b>The Facebook</b>: if you can get an invitation, this is a good place to go.  Be sure to set up a wall and enable "poke"s.</li>
<li class="fragment"><b>Angelfire</b>: Angelfire is another good place, but I can never remember my login.</li>
<li class="fragment"><b>Geocities</b>: If you have an FTP client (and `winsock.dll`) this is another good option, but be sure that you get into the right neighborhood ("Colosseum" is better than "SunsetStrip" in my opinion) and keep under the 2MB limit.</li>
</ul>

---

## The Basics (for real this time)

You'll have to address three basic things: *where*, *how* and *what*.  The first two are not completely separate, but they are often loosely-coupled.

I'm going to present my recommendations for how to set up a web presence that adheres to these requirements:

 * Looks "serious"
 * Easy to add things to without doing a ton of "web development"
 * Free-ish
 * Separates *your* identity from your *institution's* identity.

---

## Hosting Options

There are three places I recommend publishing, in decreasing order of my personal preference.  (I know some folks swap the order of the top two.)

 * Github
 * Netlify
 * Institutional homepage or other hosting provider

<div class="fragment">Can I get an idea of who has done what with these?</div>

---

## Page Creation Options

There are, roughly speaking, two ways to think about your options for page generation.

 * **Inert** pages which are served by a server without modification.  ("Static site" generators, for instance.)
 * **Active** pages that are backed by a database.  ("Blog engines," for instance.)

---

## Inert: Hugo

[Hugo](https://gohugo.io/) is a go-based package, where each page or element of content is a markdown file with metadata.

Hugo is extremely extensible with themes, styles and so forth, and can handle just about any kind of content -- including Jupyter notebooks, and themes exist to turn BibTeX files into publication lists.

Hugo is "inert" and typically the pages are built from a set of flat text files, then served.  One of the downsides to hugo is that while it's very easy to get a static site built on Github or Netlify, sometimes it's tricky to get it built locally.

My [personal homepage](https://matthewturk.github.io/) uses Hugo with the Academic theme.

---

## Inert: Jekyll

[Jekyll](https://jekyllrb.com/) is the "native" static site builder for Github pages.  It can do an awful lot!  I use it for all of my classes.

If you want to just get up and going, this is the way to go.  You can do an awful lot, but occasionally when you want to push beyond the defaults it can be sort of tricky unless you're familiar with ruby.  I do all of my coursework in Jekyll.

It uses a templating system called [Liquid](https://shopify.github.io/liquid/), which has some advantages and lots of neat filters.

---

## Active: Wordpress

Wordpress is a database-backed system that is very extensible, with WYSIWIG support for text editing and flexible layout options.

I tend not to like using Wordpress because I often feel like I can't get it to do precisely what I want, but conversely, it is a very good way to get the content management out of the way and just write things.  A downside to it is that it's often set up to look like a blog initially (but it does not *have* to be a blog) and that it requires an active server.

---

## Content: What should you have?

What are some of the basics?  Well, some of the obvious:

 * Links to other places you can be found
 * Publications, projects, collaborators

---

## Content: Beyond the Basics

I recommend you post things that take the form of writing and exploration, too.

 * It gets you in the habit of writing
 * It can lead to serendipitous collaborations
 * People like to stumble on and find cool stuff

<div class="fragment">[ramble on a bit about the delicate balance of appearing serious]</div>

---

## Automation

Your involvement in the process should be minimal.  If you host on Github or Netlify, use Github actions to automate everything.

(Github actions are awesome and can do so very much stuff.)

---

## Example Time!
