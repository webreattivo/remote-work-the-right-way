---
title:  "Famous References"
anchor: "famous_references"
type:   "dg"
h:   "h2"
---

### Books
<ul class="list-group row list-rw famousReferences">
    {% for book in site.data.famous_references_books %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            <a href="{{book.url}}" target="_blank">{{book.name}}</a>
        </li>          
    {% endfor %}      
</ul>

### Documentaries / Video
<ul class="list-group row list-rw famousReferences">
    {% for video in site.data.famous_references_videos %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            <a href="{{video.url}}" target="_blank">{{video.name}}</a>
        </li>          
    {% endfor %}      
</ul>

###Sites
<ul class="list-group row list-rw famousReferences">
    {% for site in site.data.famous_references_sites %}
        <li class="list-group-item col-xs-12 col-md-3 text-center">
            <a href="{{site.url}}" target="_blank">{{site.name}}</a>
        </li>          
    {% endfor %}      
</ul>

###Quotes
> __Jeff Atwood says:__ “I picked developers who I knew — I had incontrovertible proof — were amazing programmers. 
I’m not saying they’re perfect, far from it, merely that they were top programmers by any metric you’d care to 
measure. That’s why they were able to work remotely… 
Don’t even think about working remotely with anyone who doesn’t freakin’ bleed ones and zeros, and has a proven 
track record of getting things done.”


> __Jason Fried says:__ “Say you spend thirty minutes driving in rush hour every morning and another fifteen getting 
to your car and into the office. That’s 1.5 hours a day, 7.5 hours per week, or somewhere between 300 and 400 hours 
per year, give or take holidays and vacation. Four hundred hours is exactly the amount of programmer time we spent 
building Basecamp, our most popular product. Imagine what you could do with 400 extra hours a year. Commuting isn’t 
just bad for you, your relationships, and the environment—it’s bad for business” 