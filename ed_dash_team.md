---
title: "Ed-DaSH Team"
theme: Team
layout: page

co_investigators:
- name: Alison Meynert 
  role: Senior Research Fellow & IGC Bioinformatics Analysis Core Manager 
  affiliation: MRC Human Genetics Unit, MRC Institute of Genetics and Cancer
  img: alison_meynert.jpeg
  url: https://www.ed.ac.uk/profile/dr-alison-meynert
- name: Alex Twyford 
  role: Lecturer in Botany & Academic Lead to Edinburgh Genomics
  affiliation: School of Biological Sciences
  img: alex_twyford.jpeg
  url: http://twyford.bio.ed.ac.uk/
- name: Catalina Vallejos
  role: Chancellor’s Fellow & Fellow of the Turing Institute
  affiliation: MRC Human Genetics Unit, MRC Institute of Genetics and Cancer
  img: catalina_vallejos.jpeg
  url: https://www.ed.ac.uk/profile/catalinavallejos
- name: Edward Wallace
  role: Sir Henry Dale Fellow 
  affiliation: School of Biological Sciencs
  img: edward_wallace.jpeg
  url: https://www.ed.ac.uk/profile/dr-edward-wallace
  
programme_coordination:
- name: Giacomo Peru 
  role: Programme Coordinator
  affiliation: EPCC
  img: giacomo_peru_2.jpeg

edcarp_coordination:
- name: Giacomo Peru 
  role: Programme Coordinator
  affiliation: EPCC
  img: giacomo_peru_2.jpeg
- name: Flic Anderson
  role: Development Assistant 
  affiliation: School of Biological Sciences
  img: flic_anderson.jpeg
  
dev_computational_workflows:
- name: Alison Meynert, Co-Lead
  role: Senior Research Fellow & IGC Bioinformatics Analysis Core Manager 
  affiliation: MRC Human Genetics Unit, MRC Institute of Genetics and Cancer
  img: alison_meynert.jpeg
- name: Alex Twyford, Co-Lead
  role: Lecturer in Botany & Academic Lead to Edinburgh Genomics
  affiliation: School of Biological Sciences
  img: alex_twyford.jpeg
- name: Tim Booth
  role: Bioinformatician/Programmer
  affiliation: Edinburgh Genomics
  img: tim_booth.jpeg
- name: Nathan Medd
  role: Training and Outreach Manager
  affiliation: Edinburgh Genomics
  img: nathan_medd.jpeg
- name: Graeme Grimes
  role: Bioinformatician & IGC Bioinformatics Training Coordinator
  affiliation: MRC Human Genetics Unit, MRC Institute of Genetics and Cancer
  img: graeme_grimes.jpeg
- name: Flic Anderson
  role: Research Assistant in Bioinformatics
  affiliation: School of Biological Sciencs
  img: flic_anderson.jpeg

dev_data_man_FAIR_principles:
- name: Edward Wallace, Co-Lead
  role: Sir Henry Dale Fellow
  affiliation: School of Biological Sciences
  img: edward_wallace.jpeg
- name: Andrew Millar, Co-Lead
  role: Chair of Systems Biology & Business Owner of University Research Data Service
  affiliation: School of Biological Sciences, SynthSys
  img: andrew_millar.jpeg
- name: Andrew Romanowski
  role: Research Data Manager
  affiliation: Biological Research Data Management Team, School of Biological Sciences
  img: andrew_romanowski.jpeg
- name: Tomasz Zielinski
  role: RoleTBD
  affiliation: Biological Research Data Management Team, School of Biological Sciences
  curriculum: Data management & FAIR principles
  img: no_profile_photo.png
- name: Ines Boehm
  role: Research Consenter/Processor
  affiliation: CRUK-Tissue Group, MRC Institute of Genetics and Cancer and Royal Infirmary Edinburgh
  curriculum: Data management & FAIR principles
  img: ines_boehm.jpeg

dev_statistics:
- name: Catalina Vallejos, Co-Lead
  role: Chancellor’s Fellow & Fellow of the Turing Institute
  affiliation: MRC Human Genetics Unit, MRC Institute of Genetics and Cancer
  img: catalina_vallejos.jpeg
- name: Ailith Ewing, Co-Lead
  role: Chancellor's Fellow
  affiliation: MRC Human Genetics Unit and Cancer Research UK Edinburgh Centre, MRC Institute of Genetics and Cancer
  img: ailith_ewing.jpeg
- name: Alan O'Callaghan
  role: PhD student, Vallejos Group
  affiliation: MRC Human Genetics Unit, MRC Institute of Genetics and Cancer
  img: alan_ocallaghan.jpeg
- name: Gail Robertson
  role: RoleTBD
  affiliation: Statistical Consultancy Unit, School of Mathematics
  img: no_profile_photo.png

steering_group:
- name: Karen Halliday
  role: Dean of Systematic Inclusion & Professor and Chair of Systems Physiology
  affiliation: The College of Science and Engineering
  img: karen_halliday.jpeg
- name: Malcolm Macleod
  role: Professor of Neurology and Translational Neuroscience & University of Edinburgh Academic Lead for Research Improvement and Research Integrity
  affiliation: Centre for Clinical Brain Sciences
  img: malcolm_macleod.jpeg
- name: Mick Watson
  role: Professor of Bioinformatics and Computational Biology
  affiliation: The Roslin Institute
  img: mick_watson.jpeg
- name: Neil Chue Hong
  role: Director, Software Sustainability Institute & Senior Research Fellow
  affiliation: EPCC
  img: neil_chue_hong.jpeg
- name: Nicola Cuthbert
  role: Researcher Development Manager
  affiliation: Institute for Academic Development
  img: no_profile_photo.png
- name: Teresa Ironside
  role: Director of Data Science Education
  affiliation: Bayes Centre
  img: teresa_ironside.jpeg
  
web_development:
- name: Giacomo Peru 
  role: Programme Coordinator
  affiliation: EPCC
  img: giacomo_peru_2.jpeg
- name: Robert Nagy
  role: PhD student, Cancer Informatics Group
  affiliation: MRC IGC CRUK Edinburgh Centre
  img: robert_nagy_eddash_2.jpeg

show_heading: false  
---  

Our team brings together subject-matter expertise in ’omics, statistics, and computation, with strengths in research data management and the UK’s largest Carpentries chapter, to build an extensive cohort of confident practitioners and a scalable and sustainable network of health and bioscience data science training for the UK.

## Co-Investigators

<table class="center-cell-item">
    {% for member in page.co_investigators %}
    <tr>
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td><a href="{{ member.url }}" alt="{{ member.name }}">{{ member.name }}</a>, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
</table>

## Programme Coordination

<table class="center-cell-item">
    {% for member in page.programme_coordination: %}
    <tr> 
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td>{{ member.name }}, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
 </table>

## Development Teams

### Computational workflows

<table class="center-cell-item">
    {% for member in page.dev_computational_workflows: %}
    <tr> 
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td>{{ member.name }}, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
 </table>
 
### Data management & FAIR principles

<table class="center-cell-item">
    {% for member in page.dev_data_man_FAIR_principles: %}
    <tr> 
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td>{{ member.name }}, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
 </table>
 
### Statistics

<table class="center-cell-item">
    {% for member in page.dev_statistics: %}
    <tr> 
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td>{{ member.name }}, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
 </table>

### Website development

<table class="center-cell-item">
    {% for member in page.web_development: %}
    <tr> 
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td><b>{{ member.name }}</b>, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
 </table>
 

## Steering Group

The Ed-DaSH Steering Group is formed of the Co-investigators and Co-leads of the development teams, along with representation from across the University of Edinburgh.

<table class="center-cell-item">
    {% for member in page.steering_group: %}
    <tr> 
      <td><img src="images/profiles/{{ member.img }}" width=120 alt="{{ member.name }}"></td>
      <td>{{ member.name }}, {{ member.role }}, {{ member.affiliation }}</td>
    </tr>
    {% endfor %}
 </table>
