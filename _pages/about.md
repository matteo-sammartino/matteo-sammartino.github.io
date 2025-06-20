---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  title: Senior Lecturer (Associate Professor) in Computer Science
  affiliation: Royal Holloway University of London <br>  Centre for Programming Languages and Systems <br><br>  University College London (Honorary) 
  surface-mail: Office 2-07, Bedford building, Surrey, TW20 0EX (UK)
  phone: (+44) 01784 443690
  e-mail: matteo.sammartino [at] rhul.ac.uk  

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="me-info">
        <span class="me-title"> {{ page.profile.title }} </span> 
        <br>        
        <span>{{ page.profile.affiliation }}</span>
        <ul class="me-contacts">        
        <li><i class="fas fa-pencil-alt"></i> {{ page.profile.surface-mail }}</li>
        <li><i class="fas fa-phone"></i> {{ page.profile.phone }}</li>
        <li><i class="fas fa-envelope"></i> {{ page.profile.e-mail }}</li>
      </ul>
</div>


<!--
Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
-->