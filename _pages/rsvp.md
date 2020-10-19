---
title: "Ray and Gwen's 2021 Wedding Exxtravaganza!"
layout: splash
permalink: /rsvp/
author_profile: false
masthead: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner.jpg
---

# RSVP  

<form name="rsvp" netlify-honeypot="bot-field" action="/success/" netlify>
  <p class="hidden">
    <label>Fill this out!: <input name="bot-field" /></label>
  </p>
  <p>
    <label>Guest #1 <input type="text" name="name" required/></label>
  </p>
  <p>
    <label>Guest #2 (if applicable) <input type="text" name="plus-one" /></label>
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
    <button type="submit">Send</button>
  </p>
</form>
