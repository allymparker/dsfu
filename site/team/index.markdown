---
layout: page
title: Our Team
permalink: /team
---
<div class="row row-cols-1 row-cols-md-3 g-4">
{% for member in site.data.members %}
  <div class="col">
    <div class="card h-100 border-0">
      <img
				width="220" height="220"
				class="rounded-circle object-fit-cover mx-auto d-block mb-3"
				src="{{ member.image | relative_url }}"
				alt="{{member.name}}" />
      <div class="card-body mt-3">
        <h5 class="card-title mb-3 text-uppercase">{{member.name}}</h5>
        <p class="card-text lh-lg">{{member.blurb}}</p>
      </div>
    </div>
  </div>
{% endfor %}
</div>