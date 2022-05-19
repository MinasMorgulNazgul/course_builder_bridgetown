---
layout: course
title: Courses
paginate: 
  collection: courses
---

<div>
  <ul>
    <% paginator.resources.each do |item| %>
      <div class="box columns mt-2">
        <div class="column is-11">
          <li>
            Длительность: <%= item.data.volume %>
          </li>
          <br>
          <li class="title is-5">          
            <a href="<%= item.relative_url %>"><%= item.data.name %></a>
          </li>
        </div>
        <div class="column is-1">
          <p>&nbsp;</p>
          <p class="has-text-weight-bold"><%= item.data.price %> &#8381;</p>
          <p>&nbsp;</p>
        </div>
      </div>
    <% end %>
  </ul>
</div>
