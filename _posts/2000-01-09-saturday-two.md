---
title: "Guidelines"
bg: saturday-two
color: white
border-color: contacts
fa-icon: check-square-o	

---

# __Do adhere to the given rules.__
<div style="list-style: unset">
<hr/>

<h2> Mentors </h2>
<li> Required to maintain proper workflow of the project and provide a learning environment in the pod.</li>
<li> Allot work through making issues on the repository. Mentees will then select their choice of issue to work on. This helps in keeping track of all the work going on in the project.</li>
<li> Review PRs submitted by mentees in an appropriate period of time. It is suggested to give mentees some insights on each PR and help them improve.</li>
<li> Scoring must be done on each PR and on the same day as merging the PR.</li>
<li> Must register as a Mentee if you want to contribute to other projects.</li>
<li> Have an Enforced Contribution Guideline which cannot exclude the Organizers in any way. Ask us for a Template.</li>
<li> Be aware of how to block/ limit interactions on the repository.</li>

<hr/>
<br/>

<h2> Mentees</h2>
<li> Fulfill TASK 0 before proceeding with the event.</li>
<li> Find an issue you want to work on and get yourself assigned on it.</li>
<li> Should submit PR only after getting assigned on issue. No free pass on making PRs.</li>
<li> Follow the Contribution Guidelines.</li>
<li> Always ask Mentors for PR reviews respectfully.</li>
<li> Reply to Mentors on time and comply with tasks given.</li>

<hr/>
<br/>

<h2> General instructions</h2>
<li> Cross-project contributions are allowed and promoted. However, one should make sure to keep working adequately on their primary project.</li>
<li> Any discussion regarding the projects should be done in it’s channel on the official chat platform. This promotes the open source nature of each project and allows participants from other pods to give insights too.</li>

</div>

<!-- 
<div class="section-lines section-top section-left"></div>
{% for activity in site.data.agenda.saturday2 %}
  {% capture thecycle %}{% cycle 'even', 'odd' %}{% endcapture %}
  {% if thecycle == 'odd' %}
  {% if activity == site.data.agenda.saturday2.last %}
  <div class="activity section-left">
  {% else %}
  <div class="activity section-left section-bottom">
  {% endif %}
    <div class="row activity-info-wrapper valign-wrapper">
      <div class="col m3 activity-img valign">
        <img  src="img/{{ activity.image }}" alt="{{ activity.title }}">
      </div>
      <div class="col m9 activity-info">
        <h4 class="activity-title"> {{ activity.title }} </h4>
        <div class="col s12 activity-time">
          <i class="fa fa-clock-o"></i> <span> {{ activity.time }} </span>
        </div>
        <div class="col s12 activity-place">
          <i class="fa fa-map-marker"></i> <span> {{ activity.place }} </span>
        </div>
        <p class="col m12 activity-desc"> {{ activity.text }} </p>
        {% if activity.typeform %}
        <a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="{{ activity.typeform }}" target="blank">Inscrição</a>
        {% endif %}
      </div>
    </div>
  </div>
  {% else %}
  {% if activity == site.data.agenda.saturday2.last %}
  <div class="activity section-right">
  {% else %}
  <div class="activity section-right section-bottom">
  {% endif %}
    <div class="row activity-info-wrapper valign-wrapper">
      <div class="col m9 activity-info">
        <h4 class="activity-title"> {{ activity.title }} </h4>
        <div class="col s12 activity-time">
          <i class="fa fa-clock-o"></i> <span> {{ activity.time }} </span>
        </div>
        <div class="col s12 activity-place">
          <i class="fa fa-map-marker"></i> <span> {{ activity.place }} </span>
        </div>
        <p class="col m12 activity-desc"> {{ activity.text }} </p>
        {% if activity.typeform %}
        <a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="{{ activity.typeform }}" target="blank">Inscrição</a>
        {% endif %}
      </div>
      <div class="col m3 activity-img valign">
        <img  src="img/{{ activity.image }}" alt="{{activity.title}}">
      </div>
    </div>
  </div>
  {% endif %}
{% endfor %}
{% if thecycle == 'even' %}
<div class="section-lines section-bottom section-left"></div>
  {% else %}
<div class="section-lines section-bottom section-right"></div>
{% endif %} -->
