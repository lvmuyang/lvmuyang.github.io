---
title: "People"
permalink: "/people/"
layout: page
---

## Muyang Lu (<span class="chinese-name">吕牧羊</span>), Assistant Professor

<!-- Load Font Awesome for all icons (includes Google Scholar) -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- 楷体样式（跨浏览器/系统兼容） -->
<style>
  /* 楷体配置：覆盖不同系统的楷体字体 */
  .chinese-name {
    font-family: "KaiTi", "STKaiti", "AR PL UKai CN", "AR PL UKai HK", serif !important;
    font-style: normal; /* 避免继承斜体样式 */
    font-size: 1em; /* 匹配周边文本字号 */
    font-weight: 400; /* 常规字重，不加粗 */
  }

  /* Hover Effects (Including Google Scholar Brand Color) */
  a:hover {
    color: #3498db !important; /* Light blue for general links */
    text-decoration: underline !important;
  }
  a[href*="researchgate"]:hover {
    color: #00ccbb !important; /* ResearchGate green */
  }
  a[href*="scholar.google"]:hover {
    color: #4285F4 !important; /* Google Scholar blue (brand color) */
  }
</style>

<!-- Image Left + Text Right (Height-Aligned) -->
<div style="display: flex !important; 
            flex-wrap: wrap !important; 
            align-items: stretch !important; /* Critical: Match image/bio height */
            gap: 2rem !important; 
            max-width: 1000px !important;
            margin: 0 auto !important; 
            padding: 0 1rem !important; 
            clear: both !important;">

  <!-- Profile Image (Left) - Fixed width -->
  <div style="flex: 0 0 200px !important; 
              min-width: 180px !important;
              display: flex !important; 
              flex-direction: column !important;">
    <img 
      src="https://lvmuyang.github.io/assets/images/IMG_1919.jpeg"
      alt="Muyang Lu Profile Picture" 
      style="width: 100% !important; 
             height: auto !important;
             border-radius: 8px !important;
             box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
             border: none !important;">
  </div>

  <!-- Bio Text + Icons (Right) - Stretched to match image height -->
  <div style="flex: 1 !important; 
              min-width: 300px !important;
              display: flex !important; 
              flex-direction: column !important;
              justify-content: flex-start !important; 
              line-height: 1.6 !important;
              font-size: 16px !important;
              text-align: left !important;
              margin: 0 !important;">
    
    <!-- Bio Text -->
    Muyang’s research focuses on developing theoretical and statistical tools for macroecological studies. His work centers on niche and species distribution modeling, metacommunity dynamics, and the impacts of climate change on biodiversity.<br><br>

    Education:<br>
    -PhD, Ecology and Evolutionary Biology, Yale University<br>
    -MS, Ecology, Sun Yat-sen University<br>
    -BS, Biotechnology, Sun Yat-sen University<br><br>
    
    <!-- Icon Container (Email + CV + X + Google Scholar + ResearchGate) -->
    <div style="display: flex !important; 
                gap: 1.5rem !important; 
                align-items: center !important; 
                flex-wrap: wrap !important;">
      <!-- Email -->
      <a href="mailto:lvmuyang@scu.edu.cn" 
         style="color: #2c3e50 !important; 
                text-decoration: none !important; 
                display: inline-flex !important; 
                align-items: center !important; 
                gap: 0.5rem !important;
                font-size: 16px !important;"
         title="Email Muyang Lu">
        <i class="fas fa-envelope !important;"></i> Email
      </a>
      <!-- CV -->
      <a href="http://lvmuyang.github.io/files/CV_Muyang_Lu_2025.pdf" 
         style="color: #2c3e50 !important;
                text-decoration: none !important; 
                display: inline-flex !important; 
                align-items: center !important; 
                gap: 0.5rem !important;
                font-size: 16px !important;"
         target="_blank" 
         title="Download CV">
        <i class="fas fa-file-pdf !important;"></i> CV
      </a>
      <!-- X (Twitter) -->
      <a href="https://x.com/muyanglv" 
         style="color: #2c3e50 !important;
                text-decoration: none !important; 
                display: inline-flex !important; 
                align-items: center !important; 
                gap: 0.5rem !important;
                font-size: 16px !important;"
         target="_blank" 
         title="Follow on X (Twitter)">
        <i class="fab fa-x-twitter !important;"></i> X
      </a>
      <!-- Google Scholar (NEW) -->
      <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=D3wLjocAAAAJ" 
         style="color: #2c3e50 !important;
                text-decoration: none !important; 
                display: inline-flex !important; 
                align-items: center !important; 
                gap: 0.5rem !important;
                font-size: 16px !important;"
         target="_blank" 
         title="Google Scholar Profile">
        <i class="fab fa-google-scholar !important;"></i> Google Scholar
      </a>
      <!-- ResearchGate -->
      <a href="https://www.researchgate.net/profile/Muyang-Lu" 
         style="color: #2c3e50 !important;
                text-decoration: none !important; 
                display: inline-flex !important; 
                align-items: center !important; 
                gap: 0.5rem !important;
                font-size: 16px !important;"
         target="_blank" 
         title="Visit ResearchGate Profile">
        <i class="fab fa-researchgate !important;"></i> ResearchGate
      </a>
    </div>
  </div>
</div>
