---
title: "Team"
layout: page
---

## Muyang Lu(Lyu) 吕牧羊, Assistant Professor

<!-- Image Left + Text Right (Compatible with Jekyll "page" layout) -->
<div style="display: flex !important; /* Override layout defaults */
            flex-wrap: wrap !important; /* Wrap on mobile */
            align-items: flex-start !important; /* Align image/text to top */
            gap: 2rem !important; /* Space between image/text */
            max-width: 1000px !important;
            margin: 0 auto !important; /* Center the whole block */
            padding: 0 1rem !important; /* Prevent edge cutoff */
            clear: both !important;"> <!-- Fix layout float conflicts -->

  <!-- Profile Image (Left) - Fixed width -->
  <div style="flex: 0 0 200px !important; /* Fixed 200px width (no shrink/grow) */
              min-width: 180px !important;">
    <img 
      src="https://lvmuyang.github.io/assets/images/muyang-profile.jpg"
      alt="Muyang Lu Profile Picture" 
      style="width: 100% !important; /* Override layout image resets */
             height: auto !important;
             border-radius: 8px !important;
             box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
             border: none !important;"> <!-- Remove layout default borders -->
  </div>

  <!-- Bio Text (Right) - Adaptive width -->
  <div style="flex: 1 !important; /* Fill remaining space */
              min-width: 300px !important; /* Wrap to below image on mobile */
              line-height: 1.6 !important;
              font-size: 16px !important;
              text-align: left !important;
              margin: 0 !important;"> <!-- Override layout margin -->
    <!-- Original Bio Text -->
    Muyang’s research focuses on developing theoretical and statistical tools for macroecological studies. His work centers on niche and species distribution modeling, metacommunity dynamics, and the impacts of climate change on biodiversity.<br><br>
    
    <!-- ResearchGate Icon + Link (below bio) -->
    <a href="YOUR-RESEARCHGATE-URL-HERE" 
       style="color: #2c3e50 !important; /* Academic dark blue */
              text-decoration: none !important; 
              display: inline-flex !important; 
              align-items: center !important; 
              gap: 0.5rem !important;
              font-size: 16px !important;"
       target="_blank" 
       title="Visit Muyang Lu's ResearchGate Profile">
      <i class="fab fa-researchgate !important;"></i> ResearchGate
    </a>
  </div>
</div>
