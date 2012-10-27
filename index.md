---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

This site is dedicated to the transparency of the United States Pirate Party. Here we will have IRC logs, meeting logs, emails, chats, figures, finances, and any other documents that we can release to the public.

<h2>What You Will Find Here</h2>
Our document repo is designd to provide transparency into the United States Pirate Party. That being said, we will not share information which might invade a persons privacy, break the law, or other matters which might be sensitive. We also have uspirates.com/wiki which we will keep up for political materials, campaigns, posters, and other material. If you are looking for something on this site, but cannot find it check the wiki.

<h2>Recent Additions</h2>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
