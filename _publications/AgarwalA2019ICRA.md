---
title: "Line Coverage with Multiple Robots as a Capacitated Arc Routing Problem"
collection: publications
permalink: /publication/AgarwalA2019ICRA
excerpt: '<ul> <li>  Approach for large scale line coverage problems with multiple robots formulated as Arc Routing Problem<li>  Consideration of practical factors such as battery capacity, wind speed <li> Development of Integer Linear Programming model and heuristic algorithms'
date: 2018-05-20
venue: 'IEEE International Conference on Robotics and Automation'
paperPDF: 
citation: 'Saurav Agarwal and Srinivas Akella, &quot;Line Coverage with Multiple Robots as a Capacitated Arc Routing Problem,&quot; in <i>IEEE International Conference on Robotics and Automation</i>, May 2019 (under review).'
---
### Abstract
---
<div style="text-align: justify"> 
This paper presents an approach for solving large-
scale line coverage problems with multiple robots by formu-
lating them as Capacitated Arc Routing Problems (CARP).
Here the environment features to be inspected (e.g., power
lines, road networks) are modeled as line segments, each
robot has a specified energy constraint (i.e., battery life), and
we optimize the total cost of the tours. We first formulate
a windy capacitated arc routing problem with deadheading
demands (WCARPDD), where the costs are dependent on travel
direction and the residual robot energy capacities decrease as
they travel, as an integer linear program. We then modify
two heuristic CARP algorithms to solve the WCARPDD and
compare their performance against the optimal solutions from
the integer linear program. To tackle realistic and large scale
problems, our approach consists of a graph simplification step,
a graph partitioning step, and a robot tour generation step.
The partitioning step uses clustering techniques to partition
the large network graph of line segments to be inspected into
a set of subgraphs. For each of these subgraphs, we then solve
the WCARPDD to generate robot tours. We demonstrate our
approach, including graph simplification, on a large graph with
4,828 vertices and 4,971 edges that represents an urban region
of 16 sq. km. We present an analysis of the solutions and the
computation times of the algorithms.
</div>

 [//]: #  [Download paper here](http://academicpages.github.io/files/paper1.pdf) 

