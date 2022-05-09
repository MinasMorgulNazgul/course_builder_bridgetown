---
layout: course
name: "Film course"
technical_name: film
volume: volume
annotation: annotation
description: test123
---

```
<%= raw JSON.pretty_generate(resource.data) %>
```

```
<%= raw JSON.pretty_generate(resource.relations.units.map { |unit| unit.data }) %>
```
