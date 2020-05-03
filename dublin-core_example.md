---
layout: default
title: Dublin Core Metadata Example
description: " "
exclude: true
---

Summary Information

* * *


{% for x in site.data.dublin-core_example -%}

| Title | Creator | Subject | Description | Publisher | Contributor | Date | Type | Format | Identifier | Source | Language | Relation | Coverage | Rights |
|-------|---------|---------|-------------|-----------|-------------|------|------|--------|------------|--------|----------|----------|----------|--------|
| {{ x.Title }} | {{ x.Creator}} |{{ x.Subject}} | {{ x.Description}} | {{ x.Publisher }} | {{ x.Contributor }} | {{ x.Date}} | {{ x.Type}} | {{ x.Format}} | {{ x.Identifier}} | {{ x.Source}} | {{ x.Language}} |

{% endfor %}


 