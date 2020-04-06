---
title: "CyChecks"
summary: "Project investigating pay disparities at Iowa State"
tags: [R, Grad school]
categories: [pay equity, shiny, data cleaning]
lastmod: 2020-04-03

image:
  caption: "Hex Sticker designed by Virginia Nichols"
  focal_point: "Center"
  preview_only: false

links:
- icon: github
  icon_pack: fab
  name: Source Code
  url: https://github.com/lydiaPenglish/CyChecks2

---

### Acknowledgements: 

This was a collaborate project and would **not** have been possible without the hardworking Gina Nichols and Jarad Niemi. 

### Preamble: 

CyChecks began as a required assignment in STAT 585 at Iowa State University (ISU). As groups, we were tasked with creating a package that had data and useful functions. My collaborator and peer, Gina Nichols, had the great idea of looking at salary data from our very own university to see if there are any obvious pay disparities. Gina and I are housed in the Agronomy department, which seems to have a lot of male faculty but little female representation, despite having a largely female biased graduate program (cite?). We're able to examine salaries because ISU is a land grant school and is, in part, paid for by the taxpayer. We completed the group project with some other people, which was the original [CyChecks](https://github.com/vanichols/CyChecks). [Cy](https://en.wikipedia.org/wiki/Cy_the_Cardinal) is ISU's mascot, and Checks because...well you get it. 

The class ended in the spring of 2019, but Gina and I wanted to continue our analysis, mostly because we didn't have enough time to comb through everything we would have liked for the class project. So was born CyChecks2, which is a cleaner version of the original. 

We've focused our analysis on gender because that's what's included in the public data set. We realize there is likely an interplay between gender and rate (CITE article), however we are limited in our ability to address this interaction given the data we have. Similarly we realize that our research is considering gender as a binary and is ignoring anyone who decided to omit their gender for any reason. 

_If you're interested in the hiccups of wrangling public salary data and HR department information then check out the section at the bottom_

### What we found:

This is a work in progress and we are currently wading through things still. But our former shiny app can be found [here](https://vanichols.shinyapps.io/myapp/).

### Wrangling issues:

You guys, this was a little bit of a doozy. The reason wrangling was such a pain is that the salary database did not indicate any employee's department within the university. And while directory data in theory is public (you can Google anyone to see where they work at Iowa State), that data is not easily scrape-able. Therefore to gain access to this data we had to wade through the back-channels of ISU HR, who were super kind and helpful in giving us the information we wanted. 

But then we had issues with names. Usually middle names. Middle names were included in the salary data but not the directory data. There were duplicate names. How people designated their middle names changed over time. Sometimes there were hyphens and sometimes there weren't. The list goes on...

