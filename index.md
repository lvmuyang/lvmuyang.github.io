---
layout: default
---
<!-- No titles/headings at all -->

<!-- Add Dark/Light Mode Styling for the Title + KaiTi for Chinese Text -->
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

  /* KaiTi for Chinese characters (cross-browser compatibility) */
  .chinese-name {
    font-family: "KaiTi", "STKaiti", "AR PL UKai CN", "AR PL UKai HK", serif !important;
    font-style: normal; /* Override italic if inherited */
  }
</style>

<div align="center">
  <!-- Styled title (dark mode compatible) -->
  <h1 class="studio-title">
    Integrative Macroecology
  </h1>
  
  <!-- Abstract spatial ecology banner (main visual focus) -->
  <img src="assets/ISES.svg" alt="Abstract Spatial Ecology Visualization" width="80%" height="auto" title="Biodiversity patterns across spatial scales">

  <!-- Bio text (plain paragraph, no headings) -->
  <p style="font-size: 16px; line-height: 1.6; max-width: 800px; margin: 2rem auto; text-align: left;">
    My name is Muyang Lu (<span class="chinese-name">吕牧羊</span>). I am a theoretical ecologist based at Sichuan University, Chengdu, China (a city most famous for giant pandas and spicy hotpot).<br>
    I use mathematical and statistical tools to understand and predict macroecological patterns across scales.
  </p>
</div>
