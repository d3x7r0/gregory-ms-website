---
authors:
  - bruno-amaral
date: 2021-09-23T20:36:59+01:00
description: ""
draft: false
layout: page
resources: 
- src: images/pexels-cottonbro-6153360.jpeg
  name: "header"

rowclasses: justify-content-center align-self-center
slug:
subtitle: Stay informed about Clinical Trials and help spread the word
tags: 
  - 
categories: 
  - 
title: "For Patients"
options:
  unlisted: false
  showHeader: true
  hideFooter: false
  hideSubscribeForm: true
  header: mini
  navbar: navbar navbar-expand-lg bg-white fixed-top font-weight-bold
scripts:

menu:
  main:
    url: patients
    name: Patients
    weight: 5
---


<div class="col-md-5 col-12 justify-content-center align-self-center align-right ">
  <img src="images/undraw_mail_re_duel.svg" class="w-50 float-right d-none d-sm-block">
</div>
<div class="col-md-5 col-12 justify-content-center align-self-center ">
  <div class="col-md-12 ml-auto mr-auto">
  <div class="card card-contact card-raised">
  <form role="form" id="contact-form1" method="post" action="https://api.gregory-ms.com/subscriptions/new/">
  <div class="card-header text-center">
  <h4 class="card-title font-weight-bold">Subscribe for updates on new clinical trials</h4>
  <p class="p-3">A free service that notifies you when a clinical trial is posted on <a href="https://clinicaltrials.gov/ct2/results/rss.xml?rcv_d=14&lup_d=&sel_rss=new14&cond=Multiple+Sclerosis&count=10000" class="text-info font-weight-bold">ClinicalTrials.gov</a> or <a href="https://www.clinicaltrialsregister.eu/ctr-search/rest/feed/bydates?query=multiple+AND+sclerosis" class="text-info font-weight-bold">Clinicaltrialsregister.eu</a></p>
  </div>
  <div class="card-body">
  <div class="row">
  <div class="col-md-6 pr-2">
  <label>First name</label>
  <div class="input-group">
  <div class="input-group-prepend">
  <span class="input-group-text pr-2"><i class="now-ui-icons users_circle-08"></i></span>
  </div>
  <input type="text" name="first_name" class="form-control" placeholder="First Name..." aria-label="First Name..." autocomplete="given-name">
  </div>
  </div>
  <div class="col-md-6 pl-2">
  <div class="form-group">
  <label>Last name</label>
  <div class="input-group">
  <div class="input-group-prepend">
  <span class="input-group-text pr-2"><i class="now-ui-icons text_caps-small"></i></span>
  </div>
  <input type="text" name="last_name" class="form-control" placeholder="Last Name..." aria-label="Last Name..." autocomplete="family-name">
  </div>
  </div>
  </div>
  </div>
  <div class="form-group">
  <label>Email address</label>
  <div class="input-group">
  <div class="input-group-prepend">
  <span class="input-group-text pr-2"><i class="now-ui-icons ui-1_email-85"></i></span>
  </div>
  <input type="email" name="email" id="email" class="form-control" placeholder="Email Here..." autocomplete="email">
  </div>
  </div>
  <div class="form-group">
  <label>I am a...</label>
  <div class="input-group">
  <select id="profile" name="profile" class="form-control">
  <option value="patient">patient</option>
  <option value="doctor">doctor</option>
  <option value="clinical centre">clinical centre</option>
  </select>
  </div>
  </div>
  <div class="row">
  <div class="col-md-12 ml-auto mr-auto text-center">
  <input value="1" name="list" id="list" type="hidden">
  <button type="submit" class="btn btn-success font-weight-bold btn-lg btn-round mr-auto ml-auto">Subscribe</button>
  </div>
  </div>
  </div>
  </form>
  </div>
  </div>
</div>

<div class="w-100 mt-5 mb-5"></div>



<div class="offset-md-2 col-md-5 col-12 justify-content-center align-self-center">
  <h3 class="title text-primary">Information on this website should not be considered medical advise of any sort.</h3>
  <p>What you see here was done with no funding and by a small team. It runs on good will and donations to keep the server running.</p>
  <p>We need your help in spreading the word. Send an email to your healthcare team, share the website on your social networks and groups.</p>

  <div class="button-container">
  <a href="https://twitter.com/intent/tweet/?text=This is a free tool to help research on %23MultipleSclerosis. Help spread the word to doctors and researchers. %23health %23MS %23Neurology %23Neurotwitter https://gregory-ms.com" class="btn btn-icon btn-lg btn-twitter btn-round" data-umami-event="click--patients-page-share-twitter">
  <i class="fab fa-twitter-square"></i>
  </a>
  <a href="https://facebook.com/sharer/sharer.php?u=http%3a%2f%2fgregory-ms.com%2f" class="btn btn-icon btn-lg btn-facebook btn-round" data-umami-event="click--patients-page-share-facebook">
  <i class="fab fa-facebook-square"></i>
  </a>
  <a href="https://www.linkedin.com/shareArticle?mini=true&amp;url=http%3a%2f%2fgregory-ms.com%2f&amp;title=Gregory MS&amp;summary=A%20tool%20to%20help%20research%20on%20multiple%20sclerosis&amp;source=http%3a%2f%2fgregory-ms.com%2f" class="btn btn-lg btn-icon btn-linkedin btn-round" data-umami-event="click--patients-page-share-linkedin">
  <i class="fab fa-linkedin"></i>
  </a>
  <a href="mailto:?subject=For%20Patients&amp;body=http%3a%2f%2fgregory-ms.com%2f" class="btn btn-icon btn-lg btn-email btn-round" data-umami-event="click--patients-page-share-email">
  <svg style="width: 23px; position: absolute; top: 50%; left: 50%; transform: translate(-12px, -12px); line-height: 1.5626rem;" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="envelope" class="svg-inline--fa fa-envelope fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M502.3 190.8c3.9-3.1 9.7-.2 9.7 4.7V400c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V195.6c0-5 5.7-7.8 9.7-4.7 22.4 17.4 52.1 39.5 154.1 113.6 21.1 15.4 56.7 47.8 92.2 47.6 35.7.3 72-32.8 92.3-47.6 102-74.1 131.6-96.3 154-113.7zM256 320c23.2.4 56.6-29.2 73.4-41.4 132.7-96.3 142.8-104.7 173.4-128.7 5.8-4.5 9.2-11.5 9.2-18.9v-19c0-26.5-21.5-48-48-48H48C21.5 64 0 85.5 0 112v19c0 7.4 3.4 14.3 9.2 18.9 30.6 23.9 40.7 32.4 173.4 128.7 16.8 12.2 50.2 41.8 73.4 41.4z"></path></svg>
  </a>
  <a href="whatsapp://send?text=For%20Patients%20http%3a%2f%2fgregory-ms.com%2f" class="btn btn-lg btn-icon btn-whatsapp btn-round " data-umami-event="click--patients-page-share-twitter">
  <i class="fab fa-whatsapp"></i>
  </a>
  <a href="https://telegram.me/share/url?text=For%20Patients&amp;url=http%3a%2f%2fgregory-ms.com%2f" class="btn btn-lg btn-icon btn-telegram btn-round" data-umami-event="click--patients-page-share-telegram">
  <i class="fab fa-telegram"></i>
  </a>
  </div>
</div>



<div class="col-md-4 col-12 justify-content-center align-self-center align-left  ">
  <img src="images/undraw_Logic_re_nyb4.svg" class="float-right w-100 align-middle d-none d-md-block" alt="medical doctors" loading="lazy" />
</div>

<div class="w-100 mt-5 mb-5"></div>
</div>
<div class="row bg-grey pt-5 pb-5 mb-0 ">
<div class="col-md-6 col-12 justify-content-center align-self-center mt-5">
  <a href="https://ko-fi.com/gregoryms"><img src="images/Ko-fi_Logo_RGB.svg" class="d-none d-sm-block col-md-7" data-umami-event="click--patients-page-donate-logo-link float-right"/></a>
</div>

<div class="col-md-5 col-12 justify-content-center align-self-center align-left">
  <p>If you want to contribute to the server costs, you can send your donation through the Ko-Fi page below.</p>
  <p>We also encourage you to look at the <a href="/annual-review/">Annual Report</a> section where we keep track of donations and expenses.</p>
  <p>
  <a href="/annual-review/" class="btn btn-success btn-round btn-lg font-weight-bold" data-umami-event="click--patients-page-annual-reviews">Annual Reviews <i class="fas fa-arrow-circle-right"></i></a>
  <a href="https://ko-fi.com/gregoryms" class="btn btn-info btn-round btn-lg font-weight-bold " data-umami-event="click--patients-page-donate-text-link">Donate with Ko-Fi <i class="fas fa-mug-hot ko-fi"></i></a>
  </p>
</div>

</div>






</div>
<style>
h1,h2{text-shadow: 0 0 5px #00000091;}
div.section{padding-bottom:0;}
</style>