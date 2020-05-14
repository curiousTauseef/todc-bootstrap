---
layout: docs
title: Shadows
description: Use TODC Bootstrap's shadows to provide important visual cues about an objects’ depth and directional movement. Shadows are the only visual cue indicating the amount of separation between surfaces.
group: todc-bootstrap
toc: true
---

In need of a shadow? Add one of the <code>.shadow-*dp</code> modifier classes.

<div class="row">
{{- range (index $.Site.Data "shadows") }}
  <div class="col-md-4">
      <div class="p-3 mb-3 {{ .name }}"><code>.{{ .name }}</code></div>
  </div>
{{- end -}}
</div>

## Examples

### Alert

{{< example >}}
<div class="alert alert-primary shadow-6dp" role="alert">
  This is a primary alert—check it out!
</div>
{{< /example >}}

### Card

{{< example >}}
<div class="card shadow-8dp" style="width: 18rem;">
  {{< placeholder width="100%" height="180" class="card-img-top" text="Image cap" >}}
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
{{< /example >}}
