---
layout: default
---

{% raw %}
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
  @media screen and (max-width: 600px) {
    table {
      font-size: 12px;
    }
    
    th, td {
      padding: 5px;
    }
    
    h1 {
      font-size: 24px;
    }
    
    h2 {
      font-size: 20px;
    }
  }

  table {
    width: 100%;
    overflow-x: auto;
    display: block;
  }

  img {
    max-width: 100%;
    height: auto;
  }
</style>

<p style="text-align: right;">Last updated: {{ site.time | date: "%B %d, %Y" }}</p>

<h1 style="text-align: center;">Solana Hardware Compatibility List</h1>
{% endraw %}

{% include_relative README.md %}