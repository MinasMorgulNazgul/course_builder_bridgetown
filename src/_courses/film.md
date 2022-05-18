---
layout: course
name: "Учимся снимать фильмы"
technical_name: film
volume: 12 часов
annotation: annotation
description: test123
price: 5000
---

```
<%= raw JSON.pretty_generate(resource.data) %>
```

```
<%= raw JSON.pretty_generate(resource.relations.units.map { |unit| unit.data }) %>
```
