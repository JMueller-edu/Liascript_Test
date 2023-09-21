<!--
author:   

email:    

version:  0.0.1

language: Deutsch

narrator: Deutsch Female

comment:  

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

import:   https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md

translation: Deutsch  translations/German.md

translation: Français translations/French.md
-->

## Zielsetzung

| Jahr | 2024 | 2025 | 2026 |

## Planung Saison 23/24

```mermaid @mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section 2023/24
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2              :        des4, after des3, 5d
```