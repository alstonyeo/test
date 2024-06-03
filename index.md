---
work:
  title2: Research Director
  title: Associate Professor
  office: Blk N4, 02c-96, Nanyang Avenue. School of Computer Science and Engineering. Nanyang Technological University, Singapore 639798
  email: aseschng_at_ntu_dot_edu_dot_sg
  phone: +65 67906200
  cell: +65 67926559

  group:
    url: "https://ntunlpsg.github.io/#about"
    name: AISG Speech Lab

  department:
    url: "https://www.ntu.edu.sg/computing"
    name: College of Computing and Data Science

  university:
    url: "http://www.ntu.edu.sg"
    name: NTU
---


<div class="page-header">
  <div class="row">
    <div class="col-sm-12">
      <h3>{{ page.title }} </h3>
    </div>
  </div>

  <div class="row">
    <div class="col-sm-4">
      {% if page.scholar.id %}<a href="http://scholar.google.com/citations?user={{ page.scholar.id }}">
        <img src="img/ico/gs.png" alt=""/>
      </a> Google Scholar<br/>{% endif %}
    </div>
  </div>

  <div class="row">
    <div class="col-sm-6">
      <address>
        {{ page.work.title }}<br/>
        <a href="{{ page.work.group.url }}">{{ page.work.group.name }}</a><br/>
        Office: {{ page.work.office }}<br/> 
        <a href="{{ page.work.department.url }}">{{ page.work.department.name }}, </a> <a href="{{ page.work.university.url }}">{{ page.work.university.name }}</a> <br/> 
      </address>
    </div>
    <div class="col-sm-4">
      <a href="mailto:{{ page.work.email }}"><span class="glyphicon glyphicon-envelope"></span></a> Email<br/>
      <a href="tel:{{ page.work.phone }}"><span class="glyphicon glyphicon-phone"></span>Phone</a><br/>
      {% if page.github.id %} <a href="http://github.com/{{ page.github.id }}">
        <img src="img/ico/github_icon.png" alt=""/>
      </a> Github {% endif %}
    </div>
  </div>
</div>




<div class="row">
  <div class="col-sm-12">
    <h3> Short Biography </h3>
      <li> Associate Professor, <a href=http://www.ntu.edu.sg> Nanyang Technological University (NTU), </a>    Singapore </li>
      <li> Assistant Professor, <a href=http://www.ntu.edu.sg> Nanyang Technological University (NTU), </a>    Singapore [Jul'17 - Feb'22] </li>
      <li> Research Scientist,  <a href=http://qcri.qa/> Qatar Computing Research Institute (QCRI), </a> Doha [Jan'14 - Jul'17] </li>
      <li> PhD in Computer Science, <a href=https://www.cs.ubc.ca/> University of British Columbia (UBC),</a> Vancouver [Sep'08 - Feb'14] </li>
  </div>
</div>

<hr>


<div class="row">
  <div class="col-sm-12">
    <h3> Research Interests </h3>
  </div>
</div>

<div class="row">
  <div class="col-sm-6">
    <nlp>
      <h4> Natural Language Processing </h4>
      <li> Large Language Models (LLMs) </li>
      <li> Multi-lingual NLP (Machine Translation, Cross-lingual tasks) </li>
      <li> Multi-modal NLP  (NLP+Code, NLP+Vision) </li>
      <li> Robust/adversarial NLP  </li>
    </nlp>
  </div>
  <div class="col-sm-6">
    <ml>
      <h4> Machine Learning </h4>
      <li> Deep Learning </li>
      <li> Probabilistic Graphical Models </li>
      <li> Reinforcement Learning </li>
    </ml>
  </div>
</div>

<hr>
