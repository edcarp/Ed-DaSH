---
title: "Workshop development & delivery"
layout: page
theme: Workshops


data_sci_workflows:

- instance: "#1"
  tool: Snakemake 
  date: 2021-10-01 
  repo: "https://github.com/carpentries-incubator/snakemake-novice-bioinformatics"
  lesson: "https://carpentries-incubator.github.io/snakemake-novice-bioinformatics"
  registration: ""
- instance: #2 
  tool: Nextflow 
  date: 2021-11-01 
  repo: https://github.com/carpentries-incubator/workflows-nextflow/ 
  lesson: https://carpentries-incubator.github.io/workflows-nextflow/
  registration: ""
- instance: #3 
  tool: Snakemake 
  date: 2022-02-01 
  repo: https://github.com/carpentries-incubator/snakemake-novice-bioinformatics
  lesson: https://carpentries-incubator.github.io/snakemake-novice-bioinformatics
  registration: ""
- instance: #4 
  tool: Nextflow 
  date: 2022-03-01 
  repo: https://github.com/carpentries-incubator/workflows-nextflow/ 
  lesson: https://carpentries-incubator.github.io/workflows-nextflow/
  registration: ""
- instance: #5 
  tool: Snakemake
  date: 2022-05-01 
  repo: https://github.com/carpentries-incubator/snakemake-novice-bioinformatics 
  lesson: https://carpentries-incubator.github.io/snakemake-novice-bioinformatics 
  registration: ""
- instance: #6 
  tool: Nextflow
  date: 2022-06-01 
  repo: https://github.com/carpentries-incubator/workflows-nextflow/ 
  lesson: https://carpentries-incubator.github.io/workflows-nextflow/
  registration: ""
- instance: #7 
  tool: Snakemake 
  date: 2022-09-01 
  repo: https://github.com/carpentries-incubator/snakemake-novice-bioinformatics 
  lesson: https://carpentries-incubator.github.io/snakemake-novice-bioinformatics 
  registration: ""
- instance: #8 
  tool: Nextflow 
  date: 2022-10-01 
  repo: https://github.com/carpentries-incubator/workflows-nextflow/ 
  lesson: https://carpentries-incubator.github.io/workflows-nextflow/
  registration: ""
- instance: #9 
  tool: Snakemake 
  date: 2022-11-01 
  repo: https://github.com/carpentries-incubator/snakemake-novice-bioinformatics 
  lesson: https://carpentries-incubator.github.io/snakemake-novice-bioinformatics 
  registration: ""
- instance: #10 
  tool: Nextflow 
  date: 2023-01-01
  repo: https://github.com/carpentries-incubator/workflows-nextflow/ 
  lesson: https://carpentries-incubator.github.io/workflows-nextflow/ 
  registration: ""
- instance: #11
  tool: TBC 
  date: "" 
  repo: "" 
  lesson: "" 
  registration: ""


show_heading: false
---  



Our workshops will teach a mix of existing and new content, including new material developed
in parallel by other initiatives, to address the skills gaps most frequently identified by health and
bioscience researchers. We will use open-source platforms developed by The Carpentries, a
community-based project that is a global leader in teaching data and coding skills. The Carpentries
paradigm of open access training leads participants on a skills development path, first as a learner,
then helping an experienced instructor, finally leading instruction themselves. The Carpentries’
success and sustainability is driven by its inclusive and collaborative approach, broadening the
base of people actively engaged in learning, applying, and teaching data skills. It is a financially
sound initiative receiving generous support from major donors (e.g. Chan Zuckerberg Initiative,
Alfred P. Sloan Foundation, Gordon and Betty Moore Foundation, California Digital Library, and
Mozilla Open Source Support Program) and further financed by membership subscriptions. All
workshops will be in Carpentries format, with open-source materials deposited in The Carpentries
Incubator (hosted on GitHub) for sharing, peer review, and archiving. Mr G Peru (Edinburgh
Carpentries [EdCarp], Edinburgh Parallel Computing Centre [EPCC]) will facilitate this process as
Programme Liaison (WP4.1, 4.2).  

<br><br>

### Data Science Workflows with Snakemake and Nextflow

<table>
    <tr>
        <th>Instance</th>
        <th>Tool</th>
        <th>Date</th>
        <th>Repository</th>
        <th>Webpage</th>
        <th>Registration</th>
    </tr>
    {% for workflow in page.data_sci_workflows %}
    <tr> 
       <td>{{ workflow.instance }}</td>
       <td>{{ workflow.tool }}</td>
       <td>{{ workflow.date | "%B %Y" }}</td>
       <td><a href="{{ workflow.repo }}" target="_blank"> {{ workflow.repo }} </a></td>
       <td>[{{ workflow.lesson }}]({{ workflow.lesson }}){:target="_blank"}</td>
       <td>[{{ workflow.registration }}]({{ workflow.registration }}){:target="_blank"}</td>
    </tr>
    {% endfor %}
 </table>

 
 <br><br>


### Statistics

<table>
    <tr>
        <th>Instance</th>
        <th>Type</th>
        <th>Date</th>
        <th>Repository</th>
        <th>Webpage</th>
        <th>Registration</th>
    </tr>
    {% for item in site.statistics %}
    <tr> 
       <td>{{ item.instance }}</td>
       <td>{{ item.type }}</td>
       <td>{{ item.date | "%B %Y" }}</td>
       <td>[{{ item.repo }}]({{ item.repo }}){:target="_blank"}</td>
       <td>[{{ item.lesson }}]({{ item.lesson }}){:target="_blank"}</td>
       <td>[{{ item.registration }}]({{ item.registration }}){:target="_blank"}</td>
    </tr>
    {% endfor %}
 </table>

 
 <br><br>


### FAIR Principles in Action


<table>
    <tr>
        <th>Instance</th>
        <th>Type</th>
        <th>Date</th>
        <th>Repository</th>
        <th>Webpage</th>
        <th>Registration</th>
    </tr>
    {% for datman in site.fair_data_management %}
    <tr> 
       <td>{{ datman.instance }}</td>
       <td>{{ datman.type }}</td>
       <td>{{ datman.date | "%B %Y" }}</td>
       <td>[{{ datman.repo }}]({{ datman.repo }}){:target="_blank"}</td>
       <td>[{{ datman.lesson }}]({{ datman.lesson }}){:target="_blank"}</td>
       <td>[{{ datman.registration }}]({{ datman.registration }}){:target="_blank"}</td>
    </tr>
    {% endfor %}
 </table>

 
 <br><br>





<REMOVE ME: Below is a manually created HTML table>
    
<br>
    
## Data Science Workflows with Snakemake and Nextflow


<table>
  <tr>
   <td>Instance
   </td>
   <td>Tool
   </td>
   <td>Date
   </td>
   <td>Repository
   </td>
   <td>Webpage
   </td>
   <td>Registrations
   </td>
  </tr>
  <tr>
   <td>#1
   </td>
   <td>Snakemake
   </td>
   <td>12th-13th October 2021
   </td>
   <td>https://github.com/carpentries-incubator/snakemake-novice-bioinformatics
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#2
   </td>
   <td>Nextflow
   </td>
   <td>November 2021
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#3
   </td>
   <td>Snakemake
   </td>
   <td>February 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#4
   </td>
   <td>Nextflow
   </td>
   <td>March 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#5
   </td>
   <td>Snakemake
   </td>
   <td>May 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#6
   </td>
   <td>Nextflow
   </td>
   <td>June 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#7
   </td>
   <td>Snakemake
   </td>
   <td>September 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#8
   </td>
   <td>Nextflow
   </td>
   <td>October 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#9
   </td>
   <td>Snakemake
   </td>
   <td>November 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#10
   </td>
   <td>Nextflow
   </td>
   <td>January 2023
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#11
   </td>
   <td>TBC
   </td>
   <td>TBC
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


## Statistics


<table>
  <tr>
   <td>Instance
   </td>
   <td>Type
   </td>
   <td>Date
   </td>
   <td>Repository
   </td>
   <td>Webpage
   </td>
   <td>Registrations
   </td>
  </tr>
  <tr>
   <td>#1
   </td>
   <td>Introductory Statistics
   </td>
   <td>September 2021
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#2
   </td>
   <td>High-dimensional Statistics
   </td>
   <td>October 2021
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#3
   </td>
   <td>Machine Learning
   </td>
   <td>November 2021
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#4
   </td>
   <td>Introductory Statistics
   </td>
   <td>February 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#5
   </td>
   <td>High-dimensional Statistics
   </td>
   <td>Mar-Feb 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#6
   </td>
   <td>Machine Learning
   </td>
   <td>March 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#7
   </td>
   <td>Introductory Statistics
   </td>
   <td>May 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#8
   </td>
   <td>High-dimensional Statistics
   </td>
   <td>May-Jun 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#9
   </td>
   <td>Machine Learning
   </td>
   <td>June 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#10
   </td>
   <td>Introductory Statistics
   </td>
   <td>July 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#11
   </td>
   <td>High-dimensional Statistics
   </td>
   <td>Jul-Aug 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#12
   </td>
   <td>Machine Learning
   </td>
   <td>August 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#13
   </td>
   <td>Introductory Statistics
   </td>
   <td>September 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#14
   </td>
   <td>High-dimensional Statistics
   </td>
   <td>Sept-Oct 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#15
   </td>
   <td>Machine Learning
   </td>
   <td>October 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#16
   </td>
   <td>Introductory Statistics
   </td>
   <td>November 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#17
   </td>
   <td>High-dimensional Statistics
   </td>
   <td>January 2023
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#18
   </td>
   <td>Machine Learning
   </td>
   <td>February 2023
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


## FAIR


<table>
  <tr>
   <td>Instance
   </td>
   <td>Type
   </td>
   <td>Date
   </td>
   <td>Repository
   </td>
   <td>Webpage
   </td>
   <td>Registrations
   </td>
  </tr>
  <tr>
   <td>#1
   </td>
   <td>FAIR in Practice
   </td>
   <td>October 2021
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#2
   </td>
   <td>FAIR for Leaders
   </td>
   <td>November 2021
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#3
   </td>
   <td>FAIR in Practice
   </td>
   <td>February 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#4
   </td>
   <td>FAIR for Leaders
   </td>
   <td>March 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#5
   </td>
   <td>FAIR in Practice
   </td>
   <td>May 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#6
   </td>
   <td>FAIR for Leaders
   </td>
   <td>June 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#7
   </td>
   <td>FAIR in Practice
   </td>
   <td>July 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#8
   </td>
   <td>FAIR for Leaders
   </td>
   <td>September 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#9
   </td>
   <td>FAIR in Practice
   </td>
   <td>October 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#10
   </td>
   <td>FAIR for Leaders
   </td>
   <td>November 2022
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#11
   </td>
   <td>FAIR in Practice
   </td>
   <td>January 2023
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>#12
   </td>
   <td>FAIR for Leaders
   </td>
   <td>February 2023
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>




