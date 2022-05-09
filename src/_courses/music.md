---
layout: course
name: "Music course"
technical_name: music
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
