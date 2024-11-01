<h1 id="publications"></h1>

<h2 style="margin: 60px 0px -15px;">Under Review and Supplementary Materials</h2>

<br>
<ul>


 <li>
<a href="https://yingying.li/files/SMEconvex.pdf">Non-asymptotic Analysis of Set Membership Estimation for Linear Systems with Disturbances Bounded by Convex Sets <a style="color:#e74d3c">(Supplementary Material)</a></a>
  <br>
   Haonan Xu, <strong>Yingying Li</strong>
  <br>
   <em>Under review.</em> 
   [<a href="https://yingying.li/files/SMEconvex.pdf" style="color:#e74d3c">Supplementary Material PDF</a>]  
</li>
</ul>

<h2 style="margin: 60px 0px -15px;">Selected Publications</h2>

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
   {% if link.pdf %} 
   [<a href="{{ link.pdf }}">PDF</a>]  
   {% endif %}
   {% if link.arxiv %} 
   [<a href="{{ link.arxiv }}">arXiv</a>]  
   {% endif %}
   {% if link.code %} 
   [<a href="{{ link.code }}">Code</a>]  
   {% endif %}
   {% if link.slides %} 
   [<a href="{{ link.code }}">Slides</a>]  
   {% endif %}
   {% if link.supp %} 
   [<a href="{{ link.supp }}"><i style="color:#e74d3c">Supplementary Material</i></a>]  
   {% endif %}
   {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
   {% endif %}
</li>
<br>

{% endfor %}

</ul>
