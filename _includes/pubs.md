## Publications 

{% for publication in page.publications %}
<div class="publication">
    <div><img src="{{ publication[1].image }}" width="180px" /></div>
    <div>
    	<p markdown="1">**{{ publication[1].title }}**
    	<br />
    	{{ publication[1].authors }}
    	<br />
    	{{ publication[1].conf }}
    	<br />
    	[pdf]({{ publication[1].link }})
    	</p>
    </div>
</div>
{% endfor %}

{% include peoples_urls.md %}