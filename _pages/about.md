---
permalink: /
title: "Moke Wu"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
  .page__title {
    display: none;
  }

  /* Use more of the available width on the homepage */
  .page {
    width: 100% !important;
    float: none !important;
    padding-right: 0 !important;
  }

  .page__inner-wrap {
    width: 100%;
  }

  .home-profile {
    display: grid;
    grid-template-columns: 330px minmax(0, 1fr);
    gap: 72px;
    align-items: start;
    max-width: 1080px;
    margin: 55px auto 80px auto;
  }

  .home-photo img {
    display: block;
    width: 100%;
    max-width: 330px;
    height: auto;
    border-radius: 4px;
  }

  .home-bio h1 {
    margin: 0 0 8px 0;
    font-size: 2.25em;
    line-height: 1.15;
    font-weight: 700;
  }

  .home-position {
    margin: 0 0 30px 0;
    font-size: 1.12em;
    line-height: 1.55;
    color: #555;
  }

  .home-bio p {
    margin: 0 0 21px 0;
    line-height: 1.72;
  }

  .home-paper {
    margin-top: 28px;
    padding-top: 19px;
    border-top: 1px solid #e8e8e8;
    line-height: 1.7;
  }

  @media (max-width: 768px) {
    .home-profile {
      grid-template-columns: 1fr;
      gap: 30px;
      margin: 25px auto 55px auto;
      padding: 0 18px;
    }

    .home-photo {
      text-align: center;
    }

    .home-photo img {
      max-width: 260px;
      margin: 0 auto;
    }

    .home-bio h1 {
      font-size: 1.9em;
    }
  }
</style>

<div class="home-profile">

  <div class="home-photo">
    <img src="/images/profile.png" alt="Moke Wu">
  </div>

  <div class="home-bio">

    <h1>Moke Wu</h1>

    <p class="home-position">
      PhD Candidate in Economics<br>
      <a href="https://www.strath.ac.uk/business/economics/">University of Strathclyde</a>
    </p>

    <p>
      My research focuses on applied macroeconomics, international macroeconomics and finance,
      and Bayesian macroeconometrics. In particular, I study the macroeconomic and financial
      transmission of geopolitical risk, with an emphasis on cross-country heterogeneity and
      time variation in its transmission. Methodologically, I am particularly interested in
      Vector Autoregressions, Bayesian VARs, and Time-Varying Parameter models.
    </p>

    <p>
      My doctoral research is supervised by
      <a href="https://sites.google.com/view/sharadaniadavidson/home">Sharada Nia Davidson</a>,
      <a href="https://pingwu.org/">Ping Wu</a>, and
      <a href="https://sites.google.com/site/garykoop/">Gary Koop</a>.
    </p>

    <p>
      Prior to joining Strathclyde, I completed an MSc in Mathematical Economics and Econometrics
      at the <a href="https://economics.ed.ac.uk/">University of Edinburgh</a>
      and a BA (Hons.) in Finance at
      <a href="https://www.english.zjut.edu.cn/">Zhejiang University of Technology</a>.
    </p>

    <div class="home-paper">
      <strong>Working paper.</strong>
      My primary working paper examines how the geographic scope of geopolitical risk shapes
      international macro-financial transmission using more than 50 country-specific Bayesian VARs.
      <a href="/research/">Research →</a>
    </div>

  </div>

</div>
