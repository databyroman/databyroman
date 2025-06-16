---
date: 2024-03-12 12:26:40
layout: post
title: NBA Game ETL & Interactive Dashboard
subtitle: ETL practice
description: >-
  In this project I built a complete ETL pipeline— from raw web data to an interactive front-end:
image: https://res.cloudinary.com/dnk5l7nn0/image/upload/c_fill,w_600,h_338,ar_16:9/v1750105085/20250616_1616_Vintage_NBA_Scoreboard_simple_compose_01jxx6396ze7av3d978yrj5ghb_jenewu.png
optimized_image: https://res.cloudinary.com/dnk5l7nn0/image/upload/c_fill,w_600,h_338,ar_16:9/v1750105085/20250616_1616_Vintage_NBA_Scoreboard_simple_compose_01jxx6396ze7av3d978yrj5ghb_jenewu.png
category: ETL
tags:
  - ETL
  - API
author: Mr.Roman
---
<p>
    This project showcases a <strong>complete ETL pipeline</strong>—taking raw NBA game data from the web and turning it into an interactive dashboard.
    The main goal was to practice <em>end-to-end Extract ∙ Transform ∙ Load skills</em>.
  </p>

  <h3>Key Steps</h3>
  <ol>
    <li>
      <strong>Extract</strong> &mdash; A Python script calls the free
      <a href="https://www.balldontlie.io" target="_blank" rel="noopener">balldontlie</a> API,
      paginates safely, respects rate-limits, and stores raw JSON data.
    </li>
    <li>
      <strong>Transform</strong> &mdash; Using <code>pandas</code>, the raw data is flattened:
      columns are renamed, dates parsed, and season/team features engineered into
      a tidy <code>clean_games.csv</code>.
    </li>
    <li>
      <strong>Load</strong> &mdash; The cleaned data is pushed into a PostgreSQL
      database (<code>nba_data.games</code>) via SQLAlchemy + psycopg2.
    </li>
    <li>
      <strong>Explore</strong> &mdash; A Streamlit app connects to Postgres,
      lets users filter by season and team, and visualizes score differentials.
    </li>
  </ol>

  <h3>What I Practiced</h3>
  <ul>
    <li>API pagination &amp; rate-limit handling</li>
    <li>Data cleaning + feature engineering with <code>pandas</code></li>
    <li>Relational loading &amp; schema design in PostgreSQL</li>
    <li>Secure credential management (<code>.env</code> + <code>.gitignore</code>)</li>
    <li>Rapid dashboarding with Streamlit</li>
  </ul>

  <p>
    All code, requirements, and setup instructions are available on
    <a href="https://github.com/your-username/nba-game-etl" target="_blank" rel="noopener">GitHub</a>,
    making it easy to reproduce, schedule nightly refreshes, or plug into Tableau.
  </p>










