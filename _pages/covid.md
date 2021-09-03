---
title: "Gwen & Ray are getting married!"
layout: splash
permalink: /covid/
author_profile: false
masthead: false
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/banner-sketch.jpg
excerpt: "November 13th 2021 <br> Brooklyn, NY"
---

 [<- Home](../index.html)
{: .text-left}

# Submit your COVID-19 Vaccine Card  

<form name="rsvp" netlify-honeypot="bot-field" method="POST" data-netlify="true" action="/rsvp-success/" netlify>
  <p class="hidden">
    <label>Fill this out!: <input name="bot-field" /></label>
  </p>
  <p>
    <label>Full Name <input type="text" name="name" required/></label>
  </p>
  <p>
    <label>Vaccine Card <input type="file" name="vaccine_card" accept="image/png, image/jpeg, image/tiff, application/pdf, .heif" required/></label>
  </p>
  <p>
    <label>Questions / Comments <input type="text" name="comments" /></label>
  </p>
  <p>
    <button type="submit" class="btn btn--primary">Send</button>
  </p>
</form>
