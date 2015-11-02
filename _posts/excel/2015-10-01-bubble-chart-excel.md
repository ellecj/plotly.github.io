---
layout: excel-tutorial-single_layout
title: Make a Bubble Chart Online with Plotly and Excel
subtitle: Bubble charts with Plotly
permalink: /excel/bubble-chart
imageurl: /static/images/excel/bubble-chart/bubble-chart-thumb.jpg
state: active
tags: excel
section: Basic Charts
meta_description: A tutorial on how to make a bubble chart online with Excel.
popularity: featured
carouselimageurl: /images/bubble-carousel.jpg
actioncall: Make this Bubble Chart
actioncall-url: https://plot.ly/~jackp/14788/

similar:
 - title: Tutorial 1
   url: http://link.com
   imgurl: http://i.imgur.com/uhxCioO.png
 - title: Tutorial 2
   url: http://link.com
   imgurl: http://i.imgur.com/uhxCioO.png
 - title: Tutorial 3
   url: http://link.com
   imgurl: http://i.imgur.com/uhxCioO.png

otherlang: Know how to program? See how to create this in [Python](https://plot.ly/python/bubble-charts/) or [R](https://plot.ly/r/bubble-charts/).

live-graph: <div>
    <a href='https://plot.ly/~cimar/211/' target='_blank' title='Life Expectancy v. Per Capita GDP, 2007' style='display: block; text-align: center;'><img src='https://plot.ly/~cimar/211.png' alt='Life Expectancy v. Per Capita GDP, 2007' style='max-width: 100%;width: 560px;'  width='560' onerror='this.onerror=null;this.src='https://plot.ly/404.png';' /></a>
    <script data-plotly='cimar:211'  src='https://plot.ly/embed.js' async></script>
</div>


steps: 
 - title: Upload your Excel data to Plotly's grid
   sub-steps:
    - copy: "Open the data file for this tutorial in Excel. You can download the file here in [CSV format](https://raw.githubusercontent.com/plotly/datasets/master/bubble_chart_tutorial.csv)"
      img: "![Excel view](http://i.imgur.com/5ON7Ypp.png)"
 - title: Head to Plotly
   sub-steps:
    - copy: "Head to [Plotly's Workspace](https://plot.ly/plot) and sign into your free Plotly account. Go to 'Import', click 'Upload a file', then choose your Excel file to upload. Your Excel file will now open in Plotly's grid. For more about Plotly's grid, see [this tutorial](help.plot.ly/add-data-to-the-plotly-grid/)"
      img: "![Import data](http://i.imgur.com/eQjmxGp.png)"
 - title: Sizing and Log Axis
   sub-steps:
    - copy: "Your plot should look something like this."
      img: "![Progress](http://i.imgur.com/i0m9Oer.png)"
    - copy: "Open the TRACES popover in the toolbar."
      img: "![Traces](http://i.imgur.com/9hkxMs2.png)"
    - copy: "This is what the “Style” tab of the TRACES popover should look like for “All Traces (Bubble)”. We’ve set the “Size” field to scale the bubbles’ diameter, not area. And we’ve evened out the pixel-to-value ratio (the higher the value in the box, the smaller the bubbles will be). We’ve also increased the weight of the white bubble outlines."
      img: "![Style tab](http://i.imgur.com/wKMZtRX.png)"
    - copy: "Now, open the AXES popover in the toolbar. This is what the 'Range' tab for the X Axis looks like."
      img: ![Axes](http://i.imgur.com/zpmMa1X.png)
    - copy: "We’re opting for a log scale, which will result in a more linear plot."
      img: ![Axes2](http://i.imgur.com/ijOtC0F.png)
 - title: Style and annotate!
   sub-steps:
    - copy: "Your plot should now look something like this. In order to get the graph at the top of the chart, you’ll need to style it a little more."
      img: "![Progress3](http://i.imgur.com/ggQMO8z.png)"
    - copy: "This is what the “General” and “Margins” tabs of the LAYOUT popover should look like. We’re giving our plot a grey background, and we’ve changed some of the font options."
      img: "![General](http://i.imgur.com/OliO8BP.png)"
    - copy: "This is what the 'Lines' tab of the AXES popover looks like. We’ve changed the grey grid to white, and increased the line weight."
      img: ![Lines](http://i.imgur.com/w43GpG1.png)
    - copy: This is what the LEGEND popover looks like.  We’ve set its background to grey, too.
      img: ![Legend](http://i.imgur.com/glczRJ3.png)
    - copy: "We’ve titled our chart and axes. And we’re using markup to link to our source data using the NOTES popover. Select the 'Page' option, and hide the arrow." 
      img: ![Note](http://i.imgur.com/4CI4Lj7.png)
    - copy: Because our note has nothing to do with specific data points, we’re going to nestle it below the x-axis. Now drag it to the bottom corner of your plot.
      img: ![Note2](http://i.imgur.com/34heJSi.png)
    - copy: Once your note looks like you want it to, use the markdown &lt;a&gt; tag to link to the data source.
      img: ![Source](http://i.imgur.com/hYht3pb.png)
 - title: Export & Share
   sub-steps:
    - copy: "Download an image of your Plotly graph by clicking EXPORT on the toolbar."
      img: "![Export](http://i.imgur.com/tIGzmyp.png)"
    - copy: "Your finished chart should look something like this:"
      img: "![Finished](http://i.imgur.com/ff5feZ5.png)"
    - copy: "To add the Excel file to your workbook, click where you want to insert the picture inside Excel. On the INSERT tab inside Excel, in the ILLUSTRATIONS group, click PICTURE. Locate the Plotly graph image that you downloaded and then double-click it. Notice that we also copy-pasted the Plotly graph link in a cell for easy access to the interactive Plotly version."
      img: "![Excel](http://i.imgur.com/DpJJbQP.png)"
---