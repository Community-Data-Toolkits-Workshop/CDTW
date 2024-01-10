---
layout: default
---

<h1 class="post-title">Community Data Toolkit Workshop Event</h1>
<br />

McMaster Universities [Research Data Management Team](https://rdm.mcmaster.ca/about) in collaboration with [the Sherman Centre for Digital Scholarship](https://scds.ca/) is hosting the Community Data Toolkit Workshop event at McMaster University in Hamilton from **March 22 to 23, 2024**.


<br />


The Community Data Tools Workshop will bring together librarians and research data management professionals, researchers, and community organizations together to initiate the development of two sharable toolkits. These will be a collection of co-developed guidance documents, one with considerations and guidelines for Data Management Planning (ex. templates, draft research contracts, researcher expectations, community rights documents), and a second for Data Deposit (ex. data curation primers, legacy data inventories, or data access committee frameworks).
<br /><br /><br />

---
<br>

<h1 class="post-title">News</h1>

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
   <p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} | {{ post.date | date: "%B %-d, %Y" }}</a></p>
    <div>
        {{ post.excerpt }}<a class="excerpt" href="{{ site.baseurl }}{{ post.url }}"> Keep reading...</a>
    </div>
  </li>

{% endfor %}
</ul>
