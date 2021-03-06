<!--
# Copyright:: Copyright (c) 2012-2016 Chef Software, Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
-->

<!-- .slide: data-background="images/shaolin-masters.jpg" -->
# Chef DOJO
## DevOps Journey Assessment

Note:
This is a speaker note for the first slide



# Agenda
1. The DevOps Journey
2. DOJO Mechanics
3. Working with People
4. Working with Machines

Note:
talk about journey abstract  
how we do dojo  
ground rules



# The DevOps Journey
1. DevOps Journey Map
2. The Journey Phases
3. What You Get When We Are Done


# DevOps Journey Map
<!-- Insert revised Journey Map picture -->
![alt text](images/journey_map.png)

Note:
Orange - working with people (done in parallel)  
Blue - working with Machines (done in order)

You can make great progress in working with machines, but unless you make progress in working with people, you can't susstain it.


# The Journey Phases
+ Multiple phases can and should be worked in parallel 
+ The earlier phases evolve significantly as the journey progresses
+ It's natural to skip or inconsistently implement certain phases, so be aware of problems this causes in the later phases

Note:
As you make progress in advanced areas, such as full-stack-automation, the scope of early phases, such as testing, expands
In order to show value quickly, you will sacrifice completeness. This is technical debt. Be aware that as you try to improve your system, you will need to go back and clean up.
Revisiting is good!


### What You Get When We Are Done
<!-- Show a completed DOJO sample spider graph -->
<canvas data-chart="radar" data-chart-src="data/phase-report-example.csv" width="500" height="300">
<!--
{
"options": { "scale": { 
               "gridLines": { "color": "#FFF", "zeroLineColor": "#FFF" }, 
               "ticks": { "display": false }, 
               "pointLabels": { "fontSize": "16", "fontColor": "#FFF" }
             }
}            
}
-->
</canvas>


### What You Get When We Are Done
<!-- Show a completed DOJO sample spider graph -->
<canvas data-chart="horizontalBar" data-chart-src="data/question-report-example.csv" width="500" height="300">
<!-- 
{
"options": { 
  "responsive": true, 
  "scales": { 
    "xAxes": [{ "stacked": false }], "yAxes": [{ "stacked": true }]   
  },
  "label": { "fontColor": "#FFF" } 
}
}
-->
</canvas>

Note:
This bar chart calculates the top areas where you are looking to gain efficencies.



# DOJO Mechanics

1. Safety
2. Scoping
3. Goal Setting
4. Our Scale
5. Scoring


# Safety

This is a safe space. All of you should feel free to share openly and honestly without repercussions.

Note:
Make sure to get explicit support for this from the most senior person in the DOJO.


# Scoping

We focus on a service and the people who provide it.

+ Development
+ Operations
+ Management
+ Architecture
+ Testing
+ Security
+ Compliance
+ Release
+ Support


# Goal Setting

In this exercise, we want to assess your current state. After you have that, we want you to agree to a six month goal.

Note:
We will remind them throughout the assesement that this isn't a "I would like us to be here in 6 months", but rather "we WILL get here in 6 months"


# Our Scale

+ 0 | Not planned
+ 1 | Planned
+ 2 | Inconsistently implemented in some areas
+ 3 | Consistently implemented in some areas
+ 4 | Consistently implemented throughout the organization

Note:
Great idea to have someone in the room copy this to a whiteboard.


# Scoring

The sections of the DOJO each have a few statements. For each section, we will follow this process:

1. Individuals score each statement for current state
2. Group shares scores
3. Group discusses any differing scores
4. Consenus on scores
5. Repeat for the goal

Note:
This follows the agile process of (story sizing or planning poker )
