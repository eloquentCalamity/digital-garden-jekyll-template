---
layout: page
title: Home
id: home
permalink: /
---

#### There’s rosemary, that’s for remembrance.
#### Pray you, love, remember.



If you're interested in my various silly Magic the Gathering decks, go [here](https://rosemarysprigs.netlify.app/whydothesedecksexisthub) to ask yourself "Why do these decks exist?"    

If you want to hear about the movies and TV shows I've been watching and thinking about, head over [to this corner]().    

If you're in the market for my comments on books, you can find those [right over here](), and you can find a similar hub for comics [over in this joint](https://rosemarysprigs.netlify.app/comicsreviewshub). I have some specific hubs for entire authors, such as my boy [William Shakespeare](). More to come on individual author hubs.    

Theater is a passion of mine as well - I both act and attend shows, so I like to talk about them - more about that [over this way]().  

Being politically and intellectually active is another thing I value, so I have some writeups about things I've been reflecting on [in this section](https://rosemarysprigs.netlify.app/politicalthoughtshub).  

I'm sure more will come as I think about it and find more things I think are worth writing about. I'm glad you're here.  

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

_This digital garden template is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template). The easiest way to get started is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll). Thanks to Maxime Vaillancourt for creating the template for this site._

<style>
  .wrapper {
    max-width: 46em;
  }
  body{
    background-color: #cab3f5
  }
</style>
