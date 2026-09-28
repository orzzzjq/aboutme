<div class="publications">
<ol class="bibliography">

{% for talk in site.data.talks.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
    <div class="title">{{ talk.title }}</div>
    <div class="periodical"><em>{{ talk.venue }}{% if talk.venue and talk.date %}, {% endif %}{{ talk.date }}</em></div>
    <div class="links">
      {% if talk.slides %}
      <a href="{{ talk.slides }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Slides</a>
      {% endif %}
      {% if talk.video %}
      <a href="{{ talk.video }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Video</a>
      {% endif %}
    </div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
