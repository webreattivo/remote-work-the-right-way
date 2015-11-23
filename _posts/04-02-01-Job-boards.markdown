---
title:  "Job Boards"
anchor: "job_boards"
type:   "dg"
h:   "h2"
---
<ul class="list-group row list-rw">
{% for job in site.data.job_boards %}
    <li class="list-group-item col-xs-12 col-md-3 text-center">
        <a href="{{job.url}}" target="_blank">{{job.name}}</a>
    </li>          
{% endfor %}
</ul>