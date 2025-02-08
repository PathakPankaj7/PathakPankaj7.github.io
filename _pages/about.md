---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  body {
    margin: 0;
    padding: 0;
    height: 100%;
    position: relative;
  }

  body::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: url('/images/b1.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    opacity: 0.7; /* 70% transparent background */
    z-index: -1; /* Ensures the background stays behind the content */
  }

  .content {
    max-width: 900px;
    margin: 0 auto;
    text-align: justify;
    background: rgba(255, 255, 255, 0.85);
    padding: 30px;
    border-radius: 10px;
  }

  .footer {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  }

  .footer a img {
    width: 300px;
  }

  .footer a:last-child img {
    width: 330px;
  }
</style>

<div class="content">
  <p>Thank you for visiting my website.</p>
  <p>
    I am a Postdoctoral Research Associate at the University of Cambridge, specializing in spintronics and magnetism. I received my Ph.D. in Electrical Engineering under the supervision of 
    <a href="https://sites.google.com/site/dhimanmallick/home">Prof. Dhiman Mallick</a> at 
    <a href="https://home.iitd.ac.in/">IIT Delhi</a>, where my research focused on magnetoelectric-based spintronic and Lab-on-a-Chip devices. 
    Currently, I am working with <a href="https://www.ciccarelli.phy.cam.ac.uk/">Prof. Chiara Ciccarelli</a> at the 
    <a href="https://www.phy.cam.ac.uk/">Cavendish Laboratory</a>, focusing on superconducting spintronics.
  </p>
</div>

<div class="footer">
  <a href="https://www.cam.ac.uk/" target="_blank">
    <img src="/images/l1.jpg" alt="Logo 1">
  </a>
  <a href="https://www.phy.cam.ac.uk/" target="_blank">
    <img src="/images/l2.jpeg" alt="Logo 2">
  </a>
</div>
