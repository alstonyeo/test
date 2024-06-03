---
work:
  title: Associate Professor
  office: Blk N4, 02c-96, Nanyang Avenue. School of Computer Science and Engineering. Nanyang Technological University, Singapore 639798
  email: aseschng_at_ntu_dot_edu_dot_sg
  phone: +65 67906200
  cell: +65 67926559

  group:
    url: "https://aisingapore.org/aiproducts/speech-lab/"
    name: AISG Speech Lab

  department:
    url: "https://www.ntu.edu.sg/computing"
    name: College of Computing and Data Science

  university:
    url: "http://www.ntu.edu.sg"
    name: NTU
---

<head>
  <!-- Add Font Awesome CDN -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>

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
        <a href="{{ page.work.department.url }}">{{ page.work.department.name }}</a>, <a href="{{ page.work.university.url }}">{{ page.work.university.name }}</a><br/>
      </address>
    </div>
    <div class="col-sm-4">
      <a href="mailto:{{ page.work.email }}"><span class="fas fa-envelope"></span> Email</a><br/>
      <a href="tel:{{ page.work.phone }}"><span class="fas fa-phone"></span> Phone</a><br/>
      {% if page.github.id %} <a href="http://github.com/{{ page.github.id }}">
        <img src="img/ico/github_icon.png" alt=""/> Github
      </a>{% endif %}
    </div>
  </div>
</div>

<hr>

## Short Biography

- Associate Professor, [Nanyang Technological University (NTU)](http://www.ntu.edu.sg), Singapore [Mar'22 - ]
- Assistant Professor, [Nanyang Technological University (NTU)](http://www.ntu.edu.sg), Singapore [Jul'17 - Feb'22]
- Research Scientist, [Qatar Computing Research Institute (QCRI)](http://qcri.qa/), Doha [Jan'14 - Jul'17]
- PhD in Computer Science, [University of British Columbia (UBC)](https://www.cs.ubc.ca/), Vancouver [Sep'08 - Feb'14]

<hr>

## Research Interests

### Natural Language Processing

- Large Language Models (LLMs)
- Multi-lingual NLP (Machine Translation, Cross-lingual tasks)
- Multi-modal NLP (NLP+Code, NLP+Vision)
- Robust/adversarial NLP

### Machine Learning

- Deep Learning
- Probabilistic Graphical Models
- Reinforcement Learning

<hr>

## [Past Fundings](https://aseschng.github.io/Past_Fundings.html)
