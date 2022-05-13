---
layout: page
title:
permalink: /profiles/
---


<div class="posts">

 

 <div class="posts">
  <article class="post">
    <p>⭐️ Essays I put serious effort into</p>
    <p>🧠 Raw brain dumps</p>
  </article>


<div class="cat-nav">
  <ul>
    <li>
      <a  href="/essays">Show All</a>
    </li>
    <li>
    <a  href="/entrepreneurship" class="btn-nav">Entrepreneurship</a>
          </li>
    <li>
      <a  href="/inner-game" class="btn-nav">Inner Game</a>
    </li>
    <li>
      <a  href="/personal-brand-building" class="btn-nav">Personal Brand Building</a>
    </li>
    <li>
    <a href="/lists" class="btn-nav">Lists</a>
    </li>
    <li>
      <a  href="/notes" class="btn-nav">Book Notes</a>
    </li>
    <li>
      <a class="is-active" href="/profiles" >Profiles</a>
    </li>
  </ul>
</div>

  

  

  {% for post in site.categories.profiles %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>

<article class="post">
<p>I love reading books. But even more so I love studying how people a few steps ahead of me got to where they are now. After picking a new "target" I consume everything they've written, every podcast episode they appeared on, and spent hours researching what they actually do, not just what they say.</p> 

<p>Then I write about the patterns, ideas, and lessons I've learned from that and share them here. </p>

<p><i>Some of the notes are still work-in-progress.</i></p>
 </article>