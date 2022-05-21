---
title: "Survey"
permalink: /survey/
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/reprohum_banner_orig.jpg
---

<style>.athere:before {content: '@'; }</style>
<script type="text/javascript">
function init(){
    var x = document.getElementsByClassName('contactaddr');
    for (var i = 0; i < x.length; i++){
        var sp = x[i];
        var mt = sp.innerHTML;
        mt = mt.replace(/<span.*\/span>/, '@');
        sp.innerHTML = '<a href="mailto:' + mt + '">' + mt + '</a>';
    }
}
window.addEventListener("load", init, false);
</script>

<a href="https://docs.google.com/forms/d/e/1FAIpQLSfg1C2seS6ciHGUFdiksf3ofeMzBOtEz7HIoBw5u5YKJIxPMQ">
  <img src="/assets/images/survey_flyer.png" />
</a>
