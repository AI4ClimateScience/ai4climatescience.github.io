---
layout: about
title: about
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

# profile:
#   align: right
#   image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   address: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](http://fortawesome.github.io/Font-Awesome/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->

## Main objectives

## Topics

The bridge will overview the role of AI in modeling various aspects of climate -- atmospheric, oceanic, and land processes. For each of these topics, we will include discussions on the available data sources, the currently deployed methods, and (if any) AI approaches that have been explored in prior works. A key part of these discussions will be the limitations on both the data and modeling ends and potential solutions. Some of these questions include:

1. What are the unique biases persisting existing datasets for climate science?
2. How can we best incorporate physical domain knowledge in AI approaches?
3. How can we model multimodal climate data spanning satellite imagery, simulation data, weather balloons, etc.?
4. How robust are machine learning models for weather and climate across space and time?
5. How can we quantify and calibrate uncertainties for forecasts with machine learning models?
6. How can we scale AI infrastructure for training and inference to the petabyte-scale climate science datasets available today?


## Format

## Attendance

## Submission Requirements

## Bridge Committee

<!-- {% if page.horizontal -%}
<div class="container">
  <div class="row row-cols-2">
  {%- for project in sorted_projects -%}
    {% include projects_horizontal.html %}
  {%- endfor %}
  </div>
</div>
{%- else -%}
<div class="grid">
  {%- for project in sorted_projects -%}
    {% include projects.html %}
  {%- endfor %}
</div>
{%- endif -%} -->
<div class="grid">
  <div class="grid-sizer"></div>
  <div class="grid-item">
    <div class="card hoverable">
    <div class="card-img col-md-6">
      {%- include figure.html
            path="assets/img/12.jpg"
            alt="avatar aditya" -%}
      </div>
      <div class="col-md-6">
        <div class="card-body">
          <h2 class="card-title">Aditya Grover</h2>
          <p class="card-text">Bridge Chair, UCLA</p>
        </div>
      </div>
    </div>
  </div>
  <div class="grid-sizer"></div>
  <div class="grid-item">
    <div class="card hoverable">
      {%- include figure.html
            path="assets/img/12.jpg"
            alt="avatar jayesh" -%}
      <div class="card-body">
        <h2 class="card-title">Jayesh K. Gupta</h2>
        <p class="card-text">Microsoft</p>
      </div>
    </div>
  </div>
  <div class="grid-sizer"></div>
  <div class="grid-item">
    <div class="card hoverable">
      {%- include figure.html
            path="assets/img/12.jpg"
            alt="avatar ashish" -%}
      <div class="card-body">
        <h2 class="card-title">Ashish Kapoor</h2>
        <p class="card-text">Microsoft</p>
      </div>
    </div>
  </div>
  <div class="grid-sizer"></div>
  <div class="grid-item">
    <div class="card hoverable">
      {%- include figure.html
            path="assets/img/12.jpg"
            alt="avatar dev" -%}
      <div class="card-body">
          <h2 class="card-title">Dev Niyogi</h2>
          <p class="card-text">UT Austin</p>
      </div>
    </div>
  </div> 
  <div class="grid-sizer"></div>
  <div class="grid-item">
    <div class="card hoverable">
      {%- include figure.html
            path="assets/img/12.jpg"
            alt="avatar manmeet" -%}
      <div class="card-body">
        <h2 class="card-title">Manmeet Singh</h2>
        <p class="card-text">Indian Institute of Tropical Meteorology</p>
      </div>
    </div>
  </div>          
</div>