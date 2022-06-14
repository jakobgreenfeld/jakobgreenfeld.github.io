---
layout: page
title: 
permalink: /articles/
---




<div class="posts">
  
<article class="post">

  <strong>I write about</strong> ideas for leveling up your entrepreneurial game, building your personal brand, and breaking down invisible walls. New articles are sent to <a href="/newsletter">my email newsletter</a> every Monday and Thursday. You can read a few popular articles below or scroll down to browse recent posts.
<br> <br>
  <strong>Popular Articles</strong>
<div class="noyellowlinks">
  <ul>
    <li><a href="/personal-productivity">Effortless personal productivity (or how I learned to love my monkey mind)</a></li>
    <li><a href="/metrics">Management by metrics leads us astray</a></li>
    <li><a href="/build_an_audience">Build a business, not an audience</a></li>
    <li><a href="/stay-in-touch">A simple system I’m using to stay in touch with hundreds of people</a></li>
    <li><a href="/mba">I've decided to pursue a Bootstrap MBA</a></li>
  </ul>
</div>
</article>




<div class="cat-nav">
  <ul>
    <li>
      <a class="is-active" href="/articles">Show All</a>
    </li>
    <li>
    <a href="/entrepreneurship" class="btn-nav">Entrepreneurship</a>
          </li>
    <li>
      <a href="/inner-game" class="btn-nav">Inner Game</a>
    </li>
    <li>
      <a href="/personal-brand-building" class="btn-nav">Personal Brand Building</a>
    </li>
        <li>
    <a href="/lists" class="btn-nav">Lists</a>
          </li>
    <li>
      <a href="/notes" class="btn-nav">Book Notes</a>
    </li>
    <li>
      <a href="/profiles" class="btn-nav">Permissionless Mentors</a>
    </li>
  </ul>
</div>

  

  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}

  <article class="post">
  <h1>Legend</h1>
    <p>⭐️ Essays I put serious effort into</p>
    <p>🧠 Raw brain dumps</p>
  </article>
</div>