---
title: ACM ICPC Local Selection 
importance: 1
summary: |-
  Every year, PolyProg organizes with ACM ETHZ the Swiss Subregional local selection contest for ACM ICPC .  
  The best 6 students eligible for ICPC then participate in the South-Western European Regional Contest (SWERC).
website: /swerc
image: /images/logos/icpc.png

permalink: /swerc
---

# ACM ICPC Local Selection

The [ACM International Collegiate Programming Contest](https://icpc.global/), or ACM ICPC for short, is the biggest student programming contest in the world.
Teams first go through a regional final, and the top teams go on to the world finals.

Every year, PolyProg looks for six talented EPFL students to represent EPFL at the regional final, the [Southwestern Europe Regional Contest](https://swerc.eu/).  
These six programmers make up two teams at SWERC. 

In order to find them, we hold a selection contest.  
The contest rules are simple: contestants are given a set of problems (e.g. dynamic programming, graph algorithms, divide/conquer, ...)
and must solve as many of them as possible in the given time.

The selection contest in the 22/23 academic year will be held on **December 10, 2022 from 9:00 to 17:30 in CO5**. The contest will last 5 hours.
[Register now](https://forms.gle/VJNNkErk2xmca4Hq7)!

Schedule:    
9:00 : Check-in    
9:30 : Introduction    
9:40->10:40 : Practice Contest    
11:00->16:00 : Contest (Scoreboard Freezes at 15:00)    
16:15 : Closing ceremony    
16:30 : Apéro    

The contest is open to all EPFL students.    
Among the best students satisfying the ACM-ICPC eligibility criteria, 6 people will be selected to represent EPFL at this year's regional contest SWERC which will take place in Milano, Italy from 17/02/2023 to 19/02/2023.    

---

A few other details:    
-You will need a Codeforces account to participate. You should create this account in advance of the contest.    
-The contest is individual and the teams for SWERC will be formed later on.    
-In order to participate students need to fulfil the ACM-ICPC eligibility criteria. We will let you know by email if you're not eligible after you fill out the form.    
-You will use the computers in the room so no need to bring a laptop. However, you are allowed to bring your own keyboard if it's more comfortable for you.    
-We will provide food before, during and after the contest so no need to worry about that!     
PolyProg has participated 17 times in SWERC, and won 6 silver medals and 10 bronze medals.    

{% assign sorted_results = site.results | sort: 'id' %}
{% for result in sorted_results reversed %}
### {{ result.title }}

![Picture of SWERC {{ result.title }}]({{ site.baseurl }}{{ result.picture }})

{{ result.team1 | markdownify }}  
{{ result.team2 | markdownify }}  
{{ result.teams }} teams total

[official website]({{ result.website }})
{% endfor %}
