---
layout: page
title: Posts
---
<img src="https://res.cloudinary.com/leesheppard/image/upload/c_thumb,w_200,g_face/v1701510885/artwork/kowalla.png">

<ul>
  <% collections.posts.resources.each do |post| %>
    <li class="mb-3">
      <i class="fa-light fa-pen-swirl"></i> <a href="<%= post.relative_url %>" data-turbo="false"><%= post.data.title %></a>
    </li>
  <% end %>
</ul>
