---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!--<embed src="{{ site.baseurl }}/files/cv_minhyuk_park.pdf" width="600px" height="700px" type='application/pdf'>-->
<script type='text/javascript'>
 window.onload = function() {
    var iframe = document.createElement('iframe');
    iframe.src = "/pdf_js/web/viewer.html?file=/files/cv_minhyuk_park.pdf";
    iframe.style.width = "100%";
    iframe.style.height = "100%";
    iframe.style.frameborder = "0";
    iframe.style.borderWidth = "0";
    document.getElementById("cv-content").appendChild(iframe);
};
</script>
<div id="cv-content"></div>
<style type="text/css">
    #cv-content {
        height: 700px;
    }
</style>
