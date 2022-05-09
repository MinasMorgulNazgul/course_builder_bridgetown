---
layout: page
title: Courses
paginate: 
  collection: courses
---

<ul>
  <% paginator.resources.each do |item| %>
    <li>
      <a href="<%= item.relative_url %>"><%= item.data.name %></a>
    </li>
  <% end %>
</ul>

The list of courses is being updated
