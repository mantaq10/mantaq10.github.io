---
layout: post
date: 2026-01-22 17:30
title: TUIs vs Apple's Liquid Glass
description: No one saw it coming that 2025 will be the year of the TUI (Terminal
  User Interface) and why Apple's Liquid Glass shows a serious dearth of design leadership
  when the world needs to interact beyond AI chatbots.
image:
category:
- Design
- UI & UX
tags: apple TUI
---
<div id="chart"></div>

### Apex Charts

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var options = {
      series: [{
        name: 'series1',
        data: [31, 40, 28, 51, 42, 109, 100]
      }, {
        name: 'series2',
        data: [11, 32, 45, 32, 34, 52, 41]
      }],
      chart: {
        height: 350,
        type: 'area'
      },
      dataLabels: {
        enabled: false
      },
      stroke: {
        curve: 'smooth'
      },
      xaxis: {
        type: 'datetime',
        categories: [
          "2018-09-19T00:00:00.000Z",
          "2018-09-19T01:30:00.000Z",
          "2018-09-19T02:30:00.000Z",
          "2018-09-19T03:30:00.000Z",
          "2018-09-19T04:30:00.000Z",
          "2018-09-19T05:30:00.000Z",
          "2018-09-19T06:30:00.000Z"
        ]
      },
      tooltip: {
        x: {
          format: 'dd/MM/yy HH:mm'
        }
      }
    };

    var chart = new ApexCharts(document.querySelector("#chart"), options);
    chart.render();
  });
</script>
