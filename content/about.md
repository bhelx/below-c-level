---
title: "About"
date: 2023-01-19T23:24:27-06:00
draft: false
---

## About Us

<style>
.organizers {
  display: flex;
}
.organizer {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  padding: 20px;
}
.organizer img {
  border-radius: 50%;
  width: 175px!important;
  height: 175px!important;
  margin: unset!important; // inherited
}
@media only screen and (max-width: 600px) {
  .organizers {
    flex-direction: column;
  }
}
</style>
<div class="organizers">
  <div class="organizer">
    <img src="/images/ben.jpg" />
    <p><a href="https://github.com/bhelx">Benjamin Eckel</a> has over a decade of experience as a software engineer and is the co-founder of <a href="https://dylib.so">Dylibso</a>. He previously led DX at <a href="https://recurly.com">Recurly</a> and worked on integrations and edge observability at <a href="https://www.datadoghq.com">Datadog</a>.</p>
  </div>
  <div class="organizer">
    <img src="/images/aaron.jpg" />
    <p><a href="https://github.com/wwkeyboard">Aaron Lee</a> is a Software Engineer and SRE. He was an engineer at <a href="https://www.rackspace.com/">Rackspace</a> and <a href="https://www.digitalocean.com/">DigitalOcean</a> before building a storage system at <a href="https://www.planet.com/">Planet Labs</a>.</p>
  </div>
</div>


## What is Systems Programming?

We mostly follow the [Wikipedia definition](https://en.wikipedia.org/wiki/Systems_programming), however, we are not interested in
a strict interpretation. Instead, we want to follow the spirit of systems programming which is about curiosity of
how our computers and underlying systems work.

## Submitting a talk

Request a date in the `#below-c-level` channel in the [`Nola devs`](https://join.slack.com/t/nola/shared_invite/zt-2wwyu8rif-TCXX17XO~xSet3MCheK8uw) Slack workspace, and one of the organizers will reach out to you.

If you are new and willing to learn and talk about it, but aren't sure what to do, we'd love for you to
try something and come present your findings. Here are some ideas that could be fun:

* Make your own simple programming language
* Make a database
* Make a small virtual machine
* Make a simple OS
* Make a computer from logic gates

The intended audience is a professional programmer with several years of experience in systems programming, regardless of language, framework, or operating system. Should your presentation rely on a feature, library, syntax, etc. that's not well know outside of that specific community it will help our community if you explain it. If you have any questions we're happy to provide guidance.
