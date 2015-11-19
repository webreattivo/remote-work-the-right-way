---
title:  "Remote companies"
anchor: "remote_companies"
type:   "g"
h:   "h1"
---
<ul class="list-group row">
    {% for company in site.data.companies %}
        <li class="list-group-item col-xs-3 text-center companies">
            <img src="{{company.pathimage}}"/><br />
            <a href="{{company.url}}" target="_blank">{{company.name}}</a>
        </li>      
    {% endfor %}
</ul>