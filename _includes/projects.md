<div class="publications">
<ol class="bibliography">

{% for link in site.data.projects.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
    <div class="title">
        <a href="{{ link.link }}" target="_blank">
            {{ link.title }}
            {% if link.stars or link.forks %}(
                {% if link.stars %}
                    <i class="fa-regular fa-star" style="font-size:10pt"></i> {{ link.stars }}
                    {% if link.forks %} | {% endif %}
                {% endif %}
                {% if link.forks %}
                    <i class="fa fa-code-fork" style="font-size:10pt"></i> {{ link.forks }}
                {% endif %}
            ){% endif %}
        :</a>
        <span style="font-weight:normal">
            {{ link.description }}
        </span>
    </div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>