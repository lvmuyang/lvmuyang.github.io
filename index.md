---
layout: default
---
<!-- No titles/headings at all -->

<!-- Add Dark/Light Mode Styling for the Title + SimSun for Chinese Text -->
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

  /* 宋体样式（跨浏览器/系统兼容） */
  .chinese-name {
    font-family: "SimSun", "STSong", "AR PL SungtiL GB", serif !important;
    font-style: normal; /* 避免继承斜体样式 */
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
    My name is Muyang Lu (<span class="chinese-name">吕牧羊</span>). I am a theoretical ecologist based at Sichuan University, Chengdu, China.<br>
    I use mathematical and statistical tools to understand and predict macroecological patterns across scales.
  </p>
</div>

