---
layout: page
title: Courses
paginate: 
  collection: courses
---

<ul>
  <% paginator.resources.each do |item| %>
    <li class="title is-5">
      <a href="<%= item.relative_url %>"><%= item.data.name %></a>
    </li>
  <% end %>
</ul>

<div class="mt-6">
  <p>
    The list of courses is being updated
  </p>
</div>
