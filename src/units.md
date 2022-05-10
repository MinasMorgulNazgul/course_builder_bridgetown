---
layout: page
title: Units
paginate: 
  collection: units
---

<ul>
  <% collections.courses.resources.each do |course| %>
    <p class="subtitle is-3">For <%= course.data.name %>: </p>
    <ul class="mb-6">
      <% paginator.resources.each do |item| %>
        <% if item.data.course == course.data.technical_name %>
          <li class="title is-5">
            <a href="<%= item.relative_url %>"><%= item.data.name %></a>
          </li>
        <% end %>
      <% end %>
    </ul>
  <% end %>
</ul>

<div class="mt-6">
  <p>
    The list of units is being updated
  </p>
</div>
