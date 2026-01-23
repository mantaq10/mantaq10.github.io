---
layout: post
title: Building a Secure and Simple Website with a Learning Loop
date: 2026-01-11 19:08 +0500
description: SSGs, server side rendering is making a comeback and there is a case
  for Jekyll's lindy effect despite being dated. Its still the most secure!
image:
category:
- Tech
- Web Development
tags: jekyll ruby
---
I am thinking that the best way to do this is to write it directly from VS Code even though this is a good tool but worth the 15 dollar cost? 


Here is a **Highcharts** demo chart.
<script src="https://code.highcharts.com/highcharts.js"></script>
<div id="my-chart" style="width:100%; height:400px;"></div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    Highcharts.chart('my-chart', {
      title: { text: 'Monthly Average Temperature' },
      xAxis: {
        categories: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun',
                     'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec']
      },
      series: [{
        name: 'Tokyo',
        data: [7.0, 6.9, 9.5, 14.5, 18.2, 21.5, 25.2, 26.5, 23.3, 18.3, 13.9, 9.6]
      }]
    });
  });
</script>
