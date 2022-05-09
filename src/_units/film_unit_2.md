---
layout: unit
name: "Film - unit 2"
position: position
course: film
---

```
<%= raw JSON.pretty_generate(resource.data) %>
```

```
<%= raw JSON.pretty_generate(resource.relations.course.data) %>
```
