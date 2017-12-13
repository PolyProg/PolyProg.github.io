---
title: ACM ICPC Local Selection
importance: 1
summary: |-
  PolyProg organizes the local selection contest for ACM ICPC every year.  
  The best 6 students eligible for ICPC then participate in the South-Western European Regional Contest (SWERC).
website: /swerc
image: /images/logos/icpc.png

permalink: /swerc
---

# ACM ICPC Local Selection

The [ACM International Collegiate Programming Contest](https://icpc.baylor.edu/), or ACM ICPC for short, is the biggest student programming contest in the world.
Teams first go through a regional final, and the top teams go on to the world finals.

Every year, PolyProg looks for six talented EPFL students to represent EPFL at the regional final, the [Southwestern Europe Regional Contest](https://swerc.eu/).  
These six programmers make up two teams at SWERC. 

In order to find them, we hold a selection contest.  
The contest rules are simple: contestants are given a set of problems (e.g. dynamic programming, graph algorithms, divide/conquer, ...)
and must solve as many of them as possible in the given time.

---

PolyProg has participated 12 times in SWERC, and won 6 silver medals and 9 bronze medals.

{% assign sorted_results = site.results | sort: 'id' %}
{% for result in sorted_results reversed %}
### {{ result.title }}

![Picture of SWERC {{ result.title }}]({{ site.baseurl }}{{ result.picture }})

{{ result.team1 | markdownify }}  
{{ result.team2 | markdownify }}  
{{ result.teams }} teams total

[official website]({{ result.website }})
{% endfor %}
