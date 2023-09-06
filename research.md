<h1>Research</h1>
{% for project in site.data.projects %}
<h3>{{ project.title }}</h3>
<div class="research-tile">
    <div class="research-img">
    <img src="{{ project.image }}" alt="{{project.alt-text}}" />
    </div>
    <div class="research-description">
    <p>{{ project.description }}</p>
    </div>
</div>
{% endfor %}

<br><br><br>

<h1>Other Projects</h1>
{% for project in site.data.smaller-projects %}
<h3>{{ project.title }}</h3>
<div class="research-tile">
    <div class="research-img">
    <img src="{{ project.image }}" alt="{{project.alt-text}}" />
    </div>
    <div class="research-description">
    <p>{{ project.description }}</p>
    </div>
</div>
{% endfor %}