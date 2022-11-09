---
name: Homework 10
tools: [Python, Altair, Dataviz]
image: assets/pngs/viz_png.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Interactive Plot and Histogram

<vegachart schema-url="{{ site.baseurl }}/assets/json/interactive_chart.json" style="width: 100%"></vegachart>



# Second Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_hw.json" style="width: 100%"></vegachart>

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/nickbernier2001/Jupyter-Homework-Notebooks/blob/main/Yoo-Jacob-Grayburn-Emily-Bernier-Nick-Wongkarnta-Dorothy-Assignment10.ipynb" text="The Analysis" %}
</div>

