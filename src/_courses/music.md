---
layout: course
name: "Обучение музыке"
technical_name: music
volume: 18 часов
annotation: annotation
description: test123
price: 999
---

```
<%= raw JSON.pretty_generate(resource.data) %>
```

```
<%= raw JSON.pretty_generate(resource.relations.units.map { |unit| unit.data }) %>
```
