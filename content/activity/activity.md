---
widget: activity
widget_id: RECENT-ACTIVITY
headless: true
weight: 10

title: 实验室活动
subtitle: Activities

active: true
  
sections:
    - block: markdown
      id: activity
      content:
        title: Gallery 📸
        subtitle: '<br>'
        text: |-
          {{< gallery album="pics" order="desc">}}
      design:
        columns: '1'
---
