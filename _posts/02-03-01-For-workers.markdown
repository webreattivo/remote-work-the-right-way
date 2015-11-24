---
title:  "For workers"
anchor: "for_workers"
type:   "g"
h:   "h2"
---

### Pros
<ul class="list-group row list-rw prosCons">
    {% for pro in site.data.pros_workers %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            {{pro}} 
        </li>          
    {% endfor %}      
</ul>

### Cons
<ul class="list-group row list-rw prosCons">
    {% for con in site.data.cons_workers %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            {{con}} 
        </li>          
    {% endfor %}      
</ul>

Con: workaholism

> So, there is no commute, no office gossip, no coffee or lunch breaks with your teammates, and next to no human 
interaction. 
This could be a disastrous combination if you are prone to burnout. You’ll end up pushing yourself harder than you 
should, and 
since there’s nobody around to notice that you could use a break, chances are you won’t figure it out until it’s too 
late.

<sup>_Taken from_: [Things To Watch Out For While Working Remotely]</sup>

> I propose that most remote workers work at least as hard, if not more so, than their local counterparts. 
This is fueled in no small part by guilt and fear. We DO feel guilty working at home. 
We assume you all think we're just hanging out without pants on. 
We assume you think we're just at the mall tweeting. We fear that you think we aren't putting in a solid 40 hours (or
 50, or 60).

<sup>_Taken from_: [Being a Remote Worker Sucks - Long Live the Remote Worker]</sup>


[Things To Watch Out For While Working Remotely]: http://www.toptal.com/remote/remote-work-burnout-a-cautionary-tale
[Being a Remote Worker Sucks - Long Live the Remote Worker]: http://www.hanselman.com/blog/BeingARemoteWorkerSucksLongLiveTheRemoteWorker.aspx