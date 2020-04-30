---
layout: default
title: Data Documentation Initiative <br> Metadata Example
description: " "
---

Summary Information

* * *


|Variable | N | cat_1 | val_1 | cat_2 | val_2 | cat_3 | val_3 | cat_4 | val_4 | cat_4 | val_5 | 
|------|---|---|---|---|---|---|---|---|---|---|---|
{% for x in site.data.ddi_example -%}
| {{ x.qstnLit }} | {{ x.sum_valid}} | {{ x.cat_1_label}} | {{ x.cat_1_stat}} | {{ x.cat_2_label}} | {{ x.cat_2_stat}} | {{ x.cat_3_label}} | {{ x.cat_3_stat}} | {{ x.cat_4_label}} | {{ x.cat_4_stat}} | {{ x.cat_5_label}} | {{ x.cat_5_stat}} |

{% endfor %}

