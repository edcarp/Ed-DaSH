---
layout: landing
theme: Home
title: Ed-DaSH
logo: ![Ed-DaSH white circle logo](/images/Ed_DaSH_white_circle.png "Ed-DaSH white circle logo")


partners:
- name: UKRI
  logo_path: /images/partner_sponsor_logos/resized/UKRI-Logo_Horiz-RGB.jpg
  ref_url: https://www.ukri.org
- name: School of Biological Sciences
  logo_path:
  ref_url: https://www.ed.ac.uk/biology
- name: School of Mathematics
  logo_path: /images/partner_sponsor_logos/resized/uoe_mathematics_2_colour_small.jpg
  ref_url: https://www.maths.ed.ac.uk/
- name: Medical School (CMVM)
  logo_path: /images/partner_sponsor_logos/resized/edinburghmedicalschool_2col_cmyk_0.jpg
  ref_url: https://www.ed.ac.uk/medicine-vet-medicine/edinburgh-medical-school
- name: MRC Human Genetics Unit
  logo_path: /images/partner_sponsor_logos/resized/MRC_HGU_Edinburgh_colour_web.jpg
  ref_url: https://www.ed.ac.uk/mrc-human-genetics-unit
- name: Edinburgh Genomics
  logo_path: /images/partner_sponsor_logos/resized/edinburgh-genomics-logo_0.jpeg
  ref_url: https://genomics.ed.ac.uk/
- name: The Carpentries
  logo_path: /images/partner_sponsor_logos/resized/carpentries-hex-blue.svg 
  ref_url: https://carpentries.org
- name: Edinburgh Carpentries (EdCarp)
  logo_path: /images/partner_sponsor_logos/resized/edcarp-logo.svg
  ref_url: https://edcarp.github.io/
- name: Edinburgh International Data Facility (EIDF)
  logo_path: /images/partner_sponsor_logos/resized/eidf_web_banner_aw.jpg
  ref_url: https://www.ed.ac.uk/edinburgh-international-data-facility
- name: The Data Lab
  logo_path: /images/partner_sponsor_logos/resized/TheDataLab-Black-Logo-transparent.jpg
  ref_url: https://www.thedatalab.com/
- name: Edinburgh Parallel Computing Centre (EPCC)
  logo_path: /images/partner_sponsor_logos/resized/epcc_logo.jpeg
  ref_url: https://www.epcc.ed.ac.uk/
- name: The Software Sustainability Institute
  logo_path: /images/partner_sponsor_logos/resized/SSILogo4Citations.jpg
  ref_url: https://www.software.ac.uk/


subtitle: Edinburgh - Data Science Training in Health & Bioscience
---  


### Aims & Objectives

Our aim is to enable researchers at all career stages to harness the power of data-driven
research and innovation for health and bioscience, by providing training in the management and
analysis of biological data. We will address this aim by scaling up our successful and
oversubscribed training programs, by engaging with The Carpentries’ open platform (see below),
adding new curricula, and training new instructors. Our remotely delivered training programme will
be piloted locally and made available nationally, publicized via our strong links to organizations
involved in data science UK-wide. Our team will bring together subject-matter expertise in ’omics,
statistics, and computation, with strengths in research data management and the UK’s largest
Carpentries chapter, to build an extensive cohort of confident practitioners and a scalable and
sustainable network of health and bioscience data science training for the UK.  


1. To develop peer-reviewed training modules for biological data science that address identified skill
gaps in health and bioscience researchers (Statistics; Open science, [FAIR principles][fair]{:target="_blank"} [_Findable, Accessible, Interoperable and Reusable_] & Data Management; Data Science computing with workflows) using The Carpentries platform.

2. To deliver 98 days of remote training of our new workshops, plus established introductory material,
to a diverse community of researchers in academia and industry across all career stages.

3. To offer a clinic after every workshop for learners to ask advice regarding their own projects.

4. To train 30 new instructors to deliver these workshops, building a scalable training community.

<br>
---  
Learn more about [the project](project_overview.md).
<br>

### Curriculum development
<br>
[Developed by Ed-DaSH](curricula_overview.md)   
<br>
<hr style="width:40%">

### Workshops
<br>
[Workshops overview](workshops.md)
<br>
**Upcoming workshops**

* Reference page

<br>
**Past workshops**

* Reference page

<hr style="width:40%">
<br>
### Ed-DaSH Team
<br>
[Meet the Team](ed_dash_team.md).

<hr style="width:40%">
<br>
### Funding & Partners
<br>
We gratefully acknowledge funding from [funders]( {{ site.funders }}), under grant number 'abc'.  
<br>
[Key stakeholders](  {{ site.stakeholders }} )
<br>
<div class="logo-grid">
  {% for partner in page.partners %}
    <a class="logo-grid-item" href="{{ partner.ref_url }}"><img src="{{ partner.logo_path }}"/></a>
  {% endfor %}
</div>

<br>

[fair]: https://www.nature.com/articles/sdata201618
