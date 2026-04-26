---
layout: page
title: Posts
permalink: /blog/
---

<div class="posts-index">
  {%- assign published_posts = site.posts | where_exp: "post", "post.published != false" -%}
  {%- for post in published_posts -%}
    <article class="post-list-item">
      <h3>
        <a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </h3>
      <p class="post-meta">
        {{ post.date | date: "%b %-d, %Y" }}
        {%- if post.categories and post.categories.size > 0 -%}
          <span> · {{ post.categories | join: ", " }}</span>
        {%- endif -%}
      </p>
      {%- if post.description -%}
        <p>{{ post.description | escape }}</p>
      {%- endif -%}
    </article>
  {%- endfor -%}
</div>
