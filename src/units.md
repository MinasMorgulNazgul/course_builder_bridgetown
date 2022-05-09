---
layout: page
title: Units
paginate: 
  collection: units
---


<ul>
  <% collections.courses.resources.each do |course| %>
    <h2>For <%= course.data.name %>: </h2>
    <ul>
      <% paginator.resources.each do |item| %>
        <% if item.data.course == course.data.technical_name %>
          <li>
            <a href="<%= item.relative_url %>"><%= item.data.name %></a>
          </li>
        <% end %>
      <% end %>
    </ul>
  <% end %>
</ul>

The list of units is being updated
