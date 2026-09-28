<div class="publications">
<ol class="bibliography">

{% for teaching in site.data.teaching.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
    <div class="title">{{ teaching.title }}</div>
    <div class="periodical"><em>{{ teaching.role }}{% if teaching.role and teaching.school %}, {% endif %}{{ teaching.school }}</em></div>
    <div class="periodical"><em>{{ teaching.time }}</em></div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
