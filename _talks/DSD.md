---
title: "Pipelined MIPS Design"
collection: talks
type: "Final Project"
permalink: /talks/DSD
excerpt: "<br/><img src='/images/DSD.png' width='600' >"
venue: "Digital System Design"
date: 2019-06-01
location: "Taipei, Taiwan"
---
This is my final project of _Digital System Design_ course. We won the first prize in the competition of this project <br/>

Pipelined architecture features in high throughput. Nevertheless, if we implement MIPS by this approach, we face many relating hazards such as data hazard, jump hazard, load hazard, and branch hazard. Moreover, compared to MIPS in textbook [1], the requirements for the final project need to support the additional class of jump operations (e.g. j, jal, jr, and jalr). Thus, when designing MIPS, we divide it into several stages. First, we implement it without hazard handling. Then, we introduce data hazard and jump hazard. Finally, we complete load hazard and branch hazard. Next, extensions merely modify the chip passing the baseline. <br/>
This report is organized as follows. Section II presents the memory optimization, Section III presents the architecture optimization, and Section IV presents the extension optimization. Section V presents our synthesis settings and the corresponding results. Finally, Section VI concludes the report.
<img src='/images/DSD.png' width='600' >

[Technical Report](http://JerryHoTaiwan.github.io/files/DSD_Report.pdf)
