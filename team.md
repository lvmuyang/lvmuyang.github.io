---
title: "Team"
layout: page
---

## Muyang Lu(Lyu) 吕牧羊, Assistant Professor

<!-- Load Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- Image Left + Text Right (Height-Aligned) -->
<div style="display: flex !important; 
            flex-wrap: wrap !important; 
            align-items: stretch !important; /* Critical: Stretch items to same height */
            gap: 2rem !important; 
            max-width: 1000px !important;
            margin: 0 auto !important; 
            padding: 0 1rem !important; 
            clear: both !important;">

  <!-- Profile Image (Left) - Fixed width, image height defines container height -->
  <div style="flex: 0 0 200px !important; 
              min-width: 180px !important;
              display: flex !important; /* Align image to top of container */
              flex-direction: column !important;">
    <img 
      src="https://lvmuyang.github.io/assets/images/muyang-profile.jpg"
      alt="Muyang Lu Profile Picture" 
      style="width: 100% !important; 
             height: auto !important;
             border-radius: 8px !important;
             box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
             border: none !important;">
  </div>

  <!-- Bio Text + Icons (Right) - Stretches to match image height -->
  <div style="flex: 1 !important; 
              min-width: 300px !important;
              display: flex !important; /* Critical: Vertical layout for bio content */
              flex-direction: column !important;
              justify-content: flex-start !important; /* Keep content at top (optional) */
              line-height: 1.6 !important;
              font-size: 16px !important;
              text-align: left !important;
              margin: 0 !important;">
    
    <!-- Bio Text (top of stretched container) -->
    Muyang’s research focuses on developing theoretical and statistical tools for macroecological studies. His work centers on niche and species distribution modeling, metacommunity dynamics, and the impacts of climate change on biodiversity.<br><br>
    
    <!-- Icon Container (below bio text) -->
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
      <a href="YOUR-CV-URL-HERE" 
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

<!-- Hover Effect -->
<style>
  a:hover {
    color: #3498db !important;
    text-decoration: underline !important;
  }
  a[href*="researchgate"]:hover {
    color: #00ccbb !important;
  }
</style>
