---
name: Dashboard Using Crime Data from 2020-2024
tools: [Python, HTML, vega-lite]
image: assets/pngs/crime.png
description: This is a dashboard that plots the crimes that have occured in LA by latittude and longitude from 2020-2024.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

#  Dashboard Using Crime Data in LA from 2020-2024

<vegachart schema-url="{{ site.baseurl }}/assets/json/LA_crime_dashboard1.json" style="width: 100%"></vegachart>


```
This visualization describes the crimes in LA from 2020-2024.

```


## Jupyter Notebook

<div class="content-wrapper" style="display: flex; justify-content: space-between; align-items: center;">
  <div class="left">
    {% include elements/button.html link="https://github.com/ahmadwh2/ahmadwh2.github.io/blob/main/python_notebooks/LA_Crime_Workbook.ipynb" text="The Analysis" %}
  </div>
  <div class="right" style="margin-left: 20px; text-align: right;">
   {% include elements/button.html link="https://github.com/ahmadwh2/ahmadwh2.github.io/blob/main/assets/json/LA_crime_dashboard1.json" text="The Data" %}
  </div>
</div>


