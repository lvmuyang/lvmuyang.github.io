---
layout: default
---
<!-- No titles/headings at all -->

<!-- Add Dark/Light Mode Styling for the Title -->
<style>
  /* Light mode (default) */
  .studio-title {
    font-family: sans-serif; 
    font-style: italic; 
    font-size: 1.8rem; 
    color: #2c3e50; 
    font-weight: 500; 
    margin-bottom: 1.5rem;
  }

  /* Dark mode override */
  @media (prefers-color-scheme: dark) {
    .studio-title {
      color: white !important; /* White text in dark mode */
    }
  }
</style>

<div align="center">
  <!-- Styled title (dark mode compatible) -->
  <h1 class="studio-title">
    Integrative Spatial Ecology Studio
  </h1>
  
  <!-- Abstract spatial ecology banner (main visual focus) -->
  <img src="assets/ISES.svg" alt="Abstract Spatial Ecology Visualization" width="80%" height="auto" title="Biodiversity patterns across spatial scales">

  <!-- Bio text (plain paragraph, no headings) -->
  <p style="font-size: 16px; line-height: 1.6; max-width: 800px; margin: 2rem auto; text-align: left;">
    Our group (of which I am the only member so far 😝) is now based at Sichuan University, Chengdu, China. <br>
    We integrate theoretical, statistical, and empirical tools to understand and predict how biodiversity changes across scales.
  </p>
</div>

