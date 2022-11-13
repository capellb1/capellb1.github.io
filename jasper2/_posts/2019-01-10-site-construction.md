---
layout: post
current: post
cover: /assets/images/wo1_10/code.jpg
navigation: True
title:  "Nuts and Bolts"
date:   2019-01-10 20:19:59 -0500
tags: [Getting Started]
class: post-template
subclass: 'post'
author: blake
comments: true
---

I am skeptical that anyone would be interested in the finer details of how this blog runs, but writing it sounded fun so here we are!

For some brief exposition, believe it or not, this blog is already on its second life. It was previously used exclusively during the Spring and Summer of 2019 while I studied abroad at the University of Newcastle near Sydney, Australia. At the time, its name was "Expedition: Australia" which I admit, I still find quite badass even three years later. The site was built as two different projects: an older one-page portfolio site and a travel blog.

---

### Portfolio

The inspiration for the first half of this project came from a friend I spent the summer doing research alongside at Carnegie Mellon University (CMU). Each day after programming for eight or more hours, he would describe to me his nightly plan: to go hack away at a tricky computer science project. Not just any project, but the one that would set him apart from the crowd, which would then land him an internship at a prestigous software company, which would then land him a full time job offer at said company. Looking back on this, I am not sure if I should be impressed with his vision and determination, or concerned for his mental health as a college sophomore. Coming from a small school and having a massive chip on my shoulder, I decided I would get in on this too and spend my free time creating my own website. This was unfortunately not something I was interested in at all, but something I thought I *should* be doing to be a successful student. To say my standards for myself were high would be an understatement, and funnily enough in hindsight my measuring stick turned out to be one of the few who had the ability to make that dream a reality. 

So armed with no experience and a stable internet connection, I hunkered down and got to work. The first section of the website was built using a modified bootstrap template called "Folio" that I pulled from the internet. Think of it as someone taking the time to build a Porche and hands the keys to a toddler.  This portfolio portion of the project gave me a quick and dirty rundown on two critical components of web design, the styling language **CSS** and organizer **HTML**. And by quick and dirty, I mean I had only just enough knowledge to be dangerous, but not enough to have any clue what exactly was going on.



### Blog

The blog was added around a year later in anticipation of my trip to Australia. Rather than force my adventures onto my instagram followers, I decided that I would be more comfortable creating a semi-private space to post regular updates on my time abroad. In part, this was to keep friends and family updated, but it also served as a great way to record some incredible memories. Even today, as I ported over the old posts onto the new site, I unlocked bits of that trip that had been long forgotten. So I'd say it ended up doing its job pretty well.

Practicing what I learned in my computer science classes in college, I googled around to find out how to get the job done. I coincidentally found a beautiful open-source platform for hosting a blog, Jekyll. Jekyll is a static site generator, meaning it takes in my blog posts (as "markdown" or .md files), images, or configuration settings and spits out a website made of CSS and HTML code. Unlike most sites on the internet, there is no communication between my website and a seperate server storing images, comments, or any other content. This (theoretically) means the site loads quickly, and the contents are more secure. Although, since my website is being hosted by GitHub as a public repository, I have nothing to hide.

For my first go around, I integrated a highly customizable Jekyll template made by and called [minimalmistakes](https://mmistakes.github.io/minimal-mistakes/). Most of this work involved learning some **Ruby** (AKA downloading it and copying commands). More trickily, the integrated facebook comment section required some basic **JavaScript** and **Liquid** manipulation, which I only got partially right because there was only one comment section for *the entire website*. According to my younger self, I spent around 30 hours on the portfolio and 15 hours on the blog respectively. Now that I am working a full time job, this seems like peanuts. I'd even say I'm a bit impressed that I got a presentable website out of it, despite thinking at the time that I *should* have finished faster. Silly little me. 

That brings us to today! Having moved across the country to start a new job, living alone, I have decided to put some effort into practicing my writing skills and sharing my thoughts with the world. To do so, I revamped the blog to become a generalized, scalable and robust solution for hosting my writing. I browsed the free templates online and finally settled on a port of a professional writing website provided by the friendly company called ghost, if you look closely at the bottom of the website you will see a link to their page. The template is called [jasper2](https://jekyllt.github.io/jasper2/), and if you open the link you will see I have only made minor modifications to tailor the site for my uses. The [open-source](https://opensource.org/about) movement, which releases with complete transparency the source code of various projects like this, has played a huge part in allowing me to create this platform.

If you've made it this far, I hope you've learned something new! Cheers!

---

Original Draft:  January 10, 2019

Updates: November 12, 2022

A funny note: If I recall correctly, the reason all these programming languages are bolded is because I wanted this to serve as a resume of sorts for my programming skills. Oh, how far we have come. Its nostalgic, so I think I'll keep them in.
