<div class="publications">
<ol class="bibliography">

{% for link in site.data.teaching.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
      <div class="title"><a>{{ link.title }}</a></div>
      <div class="author">{{ link.school }}</div>
      <div class="periodical"><i>{{ link.time }}</i></div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>