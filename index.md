---
layout: page
title: "Raise your voice!"
tagline: "We are only as strong as we are united, as weak as we are divided."
published: true
---
<img src="images/route446.jpg" alt="A bus stop">
{% include JB/setup %}

Are you happy with the Route 446 services? Share your feedback with us.

## Who are we?

We are enthusiastic and passionate volunteers working with community to help solving their very local problems. We can easily be identifed by our following core values.

## Our Values
- Courage
- Care
- Togetherness
- Trust
- Happy

## Next steps

This is just the first step, rest depends on your interest and contribution.
Please like the facebook page to hear more updates and share your thoughts.

## My recent posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

