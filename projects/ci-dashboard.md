---
layout: post
title: 'CI Dashboard'
---

*Utilized: TypeScript, JavaScript, NodeJS, MySQL*

<a href="https://youtu.be/Y68BDMc2x78">
  View Demo Video (1 minute and 52 seconds) <i class="fa fa-arrow-right" aria-hidden="true"></i>
</a>

<a href="https://github.com/MikeWeiZhou/ci-dashboard">
  View GitHub Codebase <i class="fa fa-arrow-right" aria-hidden="false"></i>
</a>

This web app visualizes continuous integration performance metrics with simple moving averages to aid the optimization of project development processes.

{% include image.html image="projects/ci-dashboard/web_screenshot.png" %}

The app is designed with three main goals/requirements:

1. runs on an always-on TV screen in the office
2. easily spot trends and anomalies from visualizations
3. easily add a new custom visualization or a new data source

{% include image.html image="projects/ci-dashboard/full_screenshot.jpg" %}

For the office TV, the app automatically cycles through each category and reloads visualizations as new data comes in.

{% include image.html image="projects/ci-dashboard/visualization.jpg" %}

Dynamic moving averages, based on the selected date range, are used to better reflect trends and anomalies. Target-goals (green-dotted lines) and stretch-goals (yellow-dotted lines) are also mapped on the same visualization.

{% include image.html image="projects/ci-dashboard/simplified_architecture.jpg" %}

The architecture is divided into four layers to allow easy addition and modification to the framework we built. There are concise documentation, along with full example code and in-code documentation on how to implement a new data source or new visualization.