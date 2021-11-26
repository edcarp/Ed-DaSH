---  
title: "Workshop development & delivery"
layout: page
theme: Workshops

regulations_url: https://www.ed.ac.uk/files/atoms/files/university_computing_regulations_ay21-22_golden.pdf

show_heading: false
---  

{% assign today_date = "today" | date: "%Y-%m-%d" %}

Our workshops will teach a mix of existing and new content, including new material developed
in parallel by other initiatives, to address the skills gaps most frequently identified by health and
bioscience researchers. We will use open-source platforms developed by The Carpentries, a
community-based project that is a global leader in teaching data and coding skills. The Carpentries
paradigm of open access training leads participants on a skills development path, first as a learner,
then helping an experienced instructor, finally leading instruction themselves. The Carpentries’
success and sustainability is driven by its inclusive and collaborative approach, broadening the
base of people actively engaged in learning, applying, and teaching data skills.

<br>

## Workshop Registration


**By registering to our workshops, you agree to respect the [Computing Regulations of the University of Edinburgh]({{ page.regulations_url }}){:target="https://www.ed.ac.uk/files/atoms/files/university_computing_regulations_ay21-22_golden.pdf"}.**

<br>


 <!--table class="center-cell-item"-->
 <table class="table table-striped">
    <tr>
        <th>When</th>
        <th>Theme</th>
        <th>Workshop website</th>
        <th>Registration</th>
    </tr>
    {{ site.posts.title }}
    {% for post in site.posts %}
    {% if post.type == 'workshop_announcement' %}
    {% assign workshop_start_date = post.start_date | date: "%Y-%m-%d" %}
    <tr> 
    	<td>{{ post.when }}</td>
        <td>{{ post.title }}</td>
        <td><a href="{{ post.website }}" target="_blank">Workshop's website</a></td>
        {% if post.registration contains "https://www.epay.ed.ac.uk" and workshop_start_date > today_date %} 
       <td><a href="{{ post.registration }}" target="_blank">Register here</a></td>
       {% else %}
       <td><a style="color: #8f8f8f; "> Registration closed </a></td>
       {% endif %}
    </tr>
    {% endif %}
    {% endfor %}
 </table>


 
 <br><br>

{% comment %}{% capture workshoptime %}{{page.start_date | date: '%s' |  minus: 604800}}{% endcapture %}{% endcomment %}
