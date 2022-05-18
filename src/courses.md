---
layout: course
title: Courses
paginate: 
  collection: courses
---

<div class="columns">
  <div class="column is-11">
    <ul>
      <% paginator.resources.each do |item| %>
        <li>
          Длительность: <%= item.data.volume %>
        </li>
        <li class="title is-5">          
          <a href="<%= item.relative_url %>"><%= item.data.name %></a>
        </li>
      <% end %>
    </ul>
  </div> 
  <div class="column is-1">
    <ul>
      <% paginator.resources.each do |item| %>
        <li>
          <p>&nbsp;</p>
          <p class="has-text-weight-bold"><%= item.data.price %> &#8381;</p>
          <p>&nbsp;</p>
        </li>
      <% end %>  
    </ul>
  </div>  
</div>
