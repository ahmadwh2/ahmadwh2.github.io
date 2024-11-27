---
name: Vega Lite Example Project
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Scatter Chart Using UFO Data

<vegachart schema-url="{{ site.baseurl }}/assets/json/ufo_data_scatter.json" style="width: 100%"></vegachart>

## Search The Data & Methods

<div class="left">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/ufo-scrubbed-geocoded-time-standardized-00.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/ahmadwh2/main/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>

