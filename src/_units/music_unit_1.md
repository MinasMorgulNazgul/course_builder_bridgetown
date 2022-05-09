---
layout: unit
name: "Music - unit 1"
position: position
course: music
---

```
<%= raw JSON.pretty_generate(resource.data) %>
```

```
<%= raw JSON.pretty_generate(resource.relations.course.data) %>
```
