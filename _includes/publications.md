<h1 id="publications"></h1>

<h2 style="margin: 60px 0px -15px;">Publications</h2>

<br>
<ul>

{% for link in site.data.publications.main %}

 <li>
<a href="{{ link.pdf }}">{{ link.title }}</a>
  <br>
   {{ link.authors }}
  <br>
   <em>{{ link.conference }}</em> 
   <br>
   [<a href="{{ link.pdf }}">PDF</a>]       
   {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
</li>
<br>

{% endfor %}

</ul>
