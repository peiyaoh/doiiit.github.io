---
title: "Social Overlays: Collectively Making Websites More Usable"
category: research1
featured: true
thumbnail: /images/projects/socialoverlays/tool.png
alias: /work/socialoverlays/
tags: HCI, CSCW
abstract:
|
    Social Overlays harnesses the diversity of experience and ideas within a community to “crowd source” usability.
bullets:
|
    - [[INTERACT-2013]](http://www.irit.fr/recherches/ICS/events/conferences/interact2013/papers/8120281.pdf)

publications:
    INTERACT-2013:
        image: /images/projects/socialoverlays/tool.png
        title: "Social Overlays: Collectively Making Websites More Usable"
        authors:
        |
            [Tao Dong][td],
            [Mark Ackerman][ma],
            [Mark Newman][mwn],
            [Gaurav Paruthi][gp]
        conf: INTERACT 2013
        link: http://www.irit.fr/recherches/ICS/events/conferences/interact2013/papers/8120281.pdf
---


##Abstract

Building usable systems is challenging. In this time when websites are the face of virtually every organization, there are many cases where usability cannot be addressed as effectively as one might like, especially in nonprofit organizations. In the Social Overlays, we investigate a novel approach to creating usable websites, that is to enable users themselves to collectively improve the site.  

We developed Social Overlays, a Chrome extension, to enable end–users to identify and repair common user interface problems through creating “overlays” on web pages as part of their regular use, thereby improving usability while reducing the need for professional services. In short, Social Overlays harnesses the diversity of experience and ideas within a community to “crowd source” usability.


##Talk
<p><a href="http://dongtao.people.si.umich.edu/wp-content/uploads/2011/11/SO_INTERACT_Slides_Web.pdf" onclick="_gaq.push(['_trackEvent','download/http://dongtao.people.si.umich.edu/wp-content/uploads/2011/11/SO_INTERACT_Slides_Web.pdf']);" >Slides of the Social Overlays talk at INTERACT 2013</a></p>

##Video Demo
<p><iframe src="//www.youtube.com/embed/PlysPcqyRt0?rel=0" height="315" width="420" frameborder="0"></iframe></p>
               



{% for publication in page.publications %}
<div class="publication">
    <div><img src="{{ publication[1].image }}" width="180px" /></div>
    <div markdown="1">{{ publication[1].info }}</div>
</div>
{% endfor %}

{% include peoples_urls.md %}

