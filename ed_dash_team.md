---
title: "Ed-DaSH Who's Who"
layout: page
---


## Co-Investigators

 <table>
 <tr>
  <th>Name</th>
  <th>Role</th>
  <th>Affiliate</th>
  <th>Social</th>
 </tr>
{% for team_member in site.co_investigators %}
 <tr>
     <td>{{ team_member.name }}</td>
     <td>{{ team_member.role }}</td>
     <td>{{ team_member.affiliate }}</td>
     <td>{{ team_member.social_handler }}</td>
 </tr>
{% endfor %}
 </table>
 
 <br><br>

* Alison Meynert, Senior Research Fellow at MRC Human Genetics Unit, IGMM Bioinformatics Analysis Core Manager @ameynert
* Alex Twyford, Lecturer in Botany, SBS, Academic Lead to Edinburgh Genomics
* Catalina Vallejos, Chancellor’s Fellow at the MRC Human Genetics Unit, Fellow of the Turing Institute @catavallejos
* Edward Wallace, Sir Henry Dale Fellow, SBS, @ewallace 

## Carpentries coordination
* Programme coordinator: Giacomo Peru, EPCC @gperu
* Development assistant: Flic Anderson, SBS

## Development Teams
### Computational workflows
* Lead: Alison Meynert, Alex Twyford
* Tim Booth, Edinburgh Genomics @tbooth - Snakemake curriculum
* Nathan Medd, Edinburgh Genomics - Snakemake curriculum
* Graeme Grimes, MRC HGU @ggrimes - Nextflow curriulum
* Flic Anderson, SBS - Nextflow curriculum

### Data management & FAIR principles
* Lead: Edward Wallace - whole team working on both data management curricula
* Andrew Millar, Chair of Systems Biology, SBS; Business Owner of University Research Data Service
* Andrew Romanowski, SBS @aromanowski
* Tomasz Zielinski, SBS @tzielins

### Statistics
* Lead: Catalina Vallejos - whole team working on high dimensional statistics curriculum
* Joint Lead: Ailith Ewing, Chancellor's Fellow at MRC Human Genetics Unit and CRUK Edinburgh Centre
* Alan O'Callaghan, MRC Human Genetics Unit @Alanocallaghan
* Gail Robertson, Statistical Consultancy Unit

### Website development
* Flic Anderson, SBS - Development assistant
* Robert Nagy, CMVM: IGC ECRC [@robertn01]( {{site.rob_github}} ){:target="_blank"} 

## Steering Group
* Co-Investigators as above
* Ailith Ewing as Joint Statistics Lead
* Giacomo Peru as Programme Coordinator
* Neil Chue Hong - Director of the Software Sustainability Institute @npch
* Mick Watson - Professor of Bioinformatics and Computational Biology, The Roslin Institute
* Karen Halliday - Dean of Systematic Inclusion in The College of Science and Engineering, Professor and Chair of Systems Physiology
* Malcolm Macleod - Professor of Neurology and Translational Neuroscience, UoE
Academic Lead for Research Improvement and Research Integrity
* Nicola Cuthbert - Researcher Development Manager at Institute for Academic Development

## DI funded team members (timesheets for audit trail)

Grouped by finance team (authorization for eTime):
* SBS
  * Flic Anderson
  * Andrew Romanowski
  * Tomasz Zielinski
* Edinburgh Genomics (SBS)?
  * Tim Booth
  * Nathan Medd
* IGMM
  * Graeme Grimes
  * Alan O'Callaghan
* EPCC
  * Giacomo Peru
* School of Maths/SCU
  * Gail Robertson
