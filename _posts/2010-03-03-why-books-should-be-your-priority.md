---
date: 2018-11-22 12:26:40
layout: post
title: My First Finance Web App
subtitle:Dividend Re-Investment Calculator App
image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559822138/theme9_v273a9.jpg
optimized_image: https://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_380/v1559822138/theme9_v273a9.jpg
<a href="https://databyroman-dividend-app3-app-wk802a.streamlit.app/" target="_blank">
  <button style="padding: 10px 20px; font-size: 16px;">Launch the Calculator</button>
</a>

category: Apps
tags:
  - apps
  - Finance
author: Mr Roman
paginate: true
---

<!--page-->






<section>
  <h2>💡 Building a Dividend Growth Calculator with Streamlit and Jekyll</h2>

  <h3>🔧 Project Summary</h3>
  <p>
    In this project, we built a <strong>web-based stock investment calculator</strong> that shows how a stock investment grows over time, factoring in both <strong>price appreciation</strong> and <strong>reinvested dividends</strong>. 
    This tool is ideal for long-term investors who want to visualize the <strong>true total return</strong> of a stock—not just its price change.
  </p>

  <h3>🎯 What the App Does</h3>
  <ul>
    <li>Accepts a <code>stock symbol</code> (e.g., AAPL or MSFT) and an <strong>initial investment amount</strong></li>
    <li>Lets users select a <strong>time period</strong> with a slider (e.g., 5, 10, or 20 years)</li>
    <li>Fetches historical price and dividend data using <code>yfinance</code></li>
    <li>Calculates total portfolio value assuming <strong>automatic dividend reinvestment</strong></li>
    <li>Displays:
      <ul>
        <li>Final portfolio value</li>
        <li>Total return percentage</li>
        <li>A line chart showing growth over time</li>
      </ul>
    </li>
  </ul>

  <p>
    The result is a visual, interactive demonstration of how powerful <strong>compounding dividends</strong> can be for long-term investors.
  </p>

  <h3>🛠️ How We Built It</h3>
  <ol>
    <li>Built the app locally using <strong>Streamlit</strong> and <strong>VS Code</strong></li>
    <li>Used <code>yfinance</code> to pull historical price and dividend data</li>
    <li>Wrote Python logic to simulate dividend reinvestment over time</li>
    <li>Created an interactive interface using Streamlit (text input, sliders, charts)</li>
    <li>Deployed the app for free on <strong>Streamlit Cloud</strong></li>
    <li>Created a <strong>GitHub repository</strong> to host the code and requirements</li>
    <li>Linked the app from a personal <strong>Jekyll website</strong> using a button</li>
  </ol>

Cum sociis natoque penatibus et magnis dis `code element` montes, nascetur ridiculus mus.

```js
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
```

<!--page-->











