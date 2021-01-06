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

The selection contest in the 20/21 academic year will be held on **January 16, 2021**, starting at **14:00** on [Codeforces](https://codeforces.com/). It will last for 5 hours.
[Register now](https://go.epfl.ch/ssc2021)!

Due to the pandemic, there will be special rules this year:
- You will be able to choose between a variety of languages, including ICPC's official languages: C, C++, and Java.
- The contest will be held virtually. The contest link will be sent later per e-mail.
- This year, the contest will be open-book; you are allowed to use any online resources (incl. docs and tutorials) that were made before the contest started.
- However, all code must be written by yourself, either before or during the contest. This means that you are not allowed to copy code from other users or the internet.
- All communication between participants or with non-participants during the contest is strictly forbidden.

We will be checking the solutions for plagiarism, so make sure to follow the rules.

The contest is open to all EPFL students.
Among the best students satisfying the [ACM-ICPC eligibility criteria](http://icpc.baylor.edu/download/regionals/rules/EligibilityDecisionTree-2019.pdf), two teams of three students each will be selected to represent EPFL at the regional contest SWERC on March 6th-7th.

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
