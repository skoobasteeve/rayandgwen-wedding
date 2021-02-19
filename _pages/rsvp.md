---
title: "Gwen & Ray are getting married!"
layout: splash
permalink: /rsvp/
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

# RSVP  

<form name="rsvp" netlify-honeypot="bot-field" action="/rsvp-success/" netlify>
  <p class="hidden">
    <label>Fill this out!: <input name="bot-field" /></label>
  </p>
  <p>
    <label>Guest #1 <input type="text" name="name" required/></label>
  </p>
  <p>
    <label for="mealpref-01">Dinner Preference</label>
    <select class="form-control" id="mealpref-01" name="mealpref-01" required>
          <option value="">Choose one...</option>
          <option value="beef">Beef</option>
          <option value="chicken">Chicken</option>
          <option value="vegetarian">Vegetarian</option>
    </select>  
  </p>
  <p>
    <label>Guest #2<input type="text" name="plus-one" /></label>
  </p>
  <p>
    <label for="mealpref-02">Dinner Preference (if applicable)</label>
    <select class="form-control" id="mealpref-02" name="mealpref-02">
          <option value="">Choose one...</option>
          <option value="beef">Beef</option>
          <option value="chicken">Chicken</option>
          <option value="vegetarian">Vegetarian</option>
    </select>  
  </p>
  <p>
    <label>Email <input type="email" name="email" required/></label>
  </p>
  <p>
    <label for="attendance">Will you be attending?</label>
    <select class="form-control" id="attendance" name="attendance">
          <option value="yes">Yes</option>
          <option value="no">No</option>
    </select>  
  </p>
  <p>
    <label>Questions / Comments <input type="text" name="comments" /></label>
  </p>
  <p>
    <button type="submit" class="btn btn--primary">Send</button>
  </p>
</form>
