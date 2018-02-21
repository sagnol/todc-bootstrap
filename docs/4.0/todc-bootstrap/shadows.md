---
layout: docs
title: Shadows
description: Use TODC Bootstrap's shadows to provide important visual cues about an objects’ depth and directional movement. Shadows are the only visual cue indicating the amount of separation between surfaces.
group: todc-bootstrap
toc: true
---

In need of a shadow? Add one of the <code>.shadow-*dp</code> modifier classes.

<div class="row">
{% for shadow in site.data.shadows %}
  <div class="col-md-4">
      <div class="p-3 mb-3 {{ shadow.name }}"><code>.{{ shadow.name }}</code></div>
  </div>
{% endfor %}
</div>

## Examples

### Alert

{% example html %}
<div class="alert alert-primary shadow-6dp" role="alert">
  This is a primary alert—check it out!
</div>
{% endexample %}

### Card

{% example html %}
<div class="card shadow-8dp" style="width: 18rem;">
  <img class="card-img-top" src="holder.js/100px180/" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
{% endexample %}