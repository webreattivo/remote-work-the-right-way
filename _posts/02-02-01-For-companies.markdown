---
title:  "For companies"
anchor: "for_companies"
type:   "g"
h:   "h2"
---

### Pros
<ul class="list-group row list-rw prosCons">
    {% for pro in site.data.pros_companies %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            {{pro}} 
        </li>          
    {% endfor %}      
</ul>


Pro: It’s more eco-friendly

> As a remote employer, each member of your workforce who works from home greatly reduces his carbon footprint 
by not having to commute into the office. Fewer office supplies are used, and energy used to run their 
home offices is also lessened.                

Pro: Your staff will be in better health

> With more time in their workday, remote workers often incorporate more physical exercise into their day than office
 workers, 
who are either stuck in the office or commuting to and from their homes.

Pro: They’ll be more loyal

> When you give your employees the ability to customize their schedule so that they can better balance their 
professional life 
and their personal life, an interesting thing happens: they become grateful

<sup>_Taken from_: [6 Interesting Benefits of Remote Work](https://remote.co/6-interesting-benefits-of-remote-work/)</sup>              

### Cons
<ul class="list-group row list-rw prosCons">
    {% for con in site.data.cons_companies %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            {{con}} 
        </li>          
    {% endfor %}      
</ul>