---
title:  "Marketplaces"
anchor: "marketplaces"
type:   "g"
h:   "h2"
---
<ul class="list-group row list-rw">
{% for marketplace in site.data.marketplaces %}
    <li class="list-group-item col-xs-12 col-md-3 text-center">
        <a href="{{marketplace.url}}" target="_blank">{{marketplace.name}}</a>
    </li>          
{% endfor %}
</ul>