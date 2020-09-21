---
layout: default
title:  "Convex Optimization"
date:   2020-06-01
categories: motion planning
icon:	"364_main.JPG"
---

<h1>Convex Optimization</h1>

As part of a convex optimization course, a classmate and I implemented multi-agent trajectory optimization. In the example below, each agent has required waypoint locations that it must reach at various times and must traverse without colliding with one another. In addition, the trajectory for each vehicle must be dynamically feasible. Each image below shows the locations of the vehicles at a particular time as well as the full path for all vehicles. The leftmost image in each row is one of the waypoint locations (ex. square formation in the first image). A final constraint on this example is that the paths must by cyclic, i.e. that each vehicle must end where it started.

<div class="box alt">
<div class="row uniform">
<div class="12u$"><span class="image fit"><img src="{{ site.url }}{{ site.baseurl }}/images/364_main.JPG" alt="" /></span></div>
</div>
</div>
