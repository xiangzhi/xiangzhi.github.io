# On-Going Projects
The following are some of my on-going research projects.

{% for project in site.data.on-going-projects %}
<h3>{{ project.title }}</h3>
<div>
    <!-- <div class="research-img">
    <img src="{{ project.image }}" alt="{{project.alt-text}}" />
    </div> -->
    <p>{{ project.description }}</p>
</div>
{% endfor %}