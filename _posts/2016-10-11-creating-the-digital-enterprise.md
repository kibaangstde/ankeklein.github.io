---
layout: post
title: Application Modernization&#58; Creating the Digital Enterprise
comments: true
permalink: /presentations/creating-the-digital-enterprise
category: presentation
image: /img/paper.jpg
---

Competitive pressures are forcing companies to look for the ways to differentiate and innovate their business using technology. Business and user demands are changing at a fast pace. In a digital business it is no longer about saving money on IT. It is no longer about IT operating with greater efficiency.

Instead it is about how IT can be used as a differentiator to boost business growth, to create better offerings and to deliver a better user experience. Digital transformation is essential to be disruptive and / or sustain in disruptive competition. In this session we will present our approach for achieving digital transformation which is based on the three pillars of change:

- Architecture: Transforming applications to a cloud native architecture
- People and processes: Combining skills in a DevOps approach
- Platform: how you deploy and operate will be different: OpenShift container management Platform

<hr />
  <div>
    <h3>PROJECTLEDEN</h3>
  </div>
  <div class="row">
    {% for staff_member in site.staff_members %}
    {%if staff_member.alumni %}
    <div class="column">
      <div class="article">
        <div class="article-head">
          <img src="{{ site.url }}{{staff_member.image}}" />
        </div>
        <div class="article-content">
          <h4>{{ staff_member.name }}</h4>
          <h5>{{ staff_member.title }}</h5>
          <p class="article-summary">{{ staff_member.summary }}</p>
        </div>
      </div>
    </div>
    {% endif %}
    {% endfor %}
  </div>
