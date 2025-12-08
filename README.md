---
title: "Team"
layout: page
---
---

## Muyang Lu(Lyu) 吕牧羊, Assistant Professor

<!-- Image LEFT, Text RIGHT (fixed layout) -->
<div style="display: flex; 
            flex-direction: row; /* Forces horizontal layout (left-right) */
            flex-wrap: wrap; /* Wraps to vertical on mobile (responsive) */
            gap: 2rem; /* Space between image and text */
            align-items: flex-start; /* Aligns image/text to the top */
            max-width: 1000px; 
            margin: 0 auto; /* Centers the whole block on page */
            padding: 0 1rem;"> <!-- Prevents edge cutoff on small screens -->
  
  <!-- Profile Picture (LEFT column) -->
  <div style="flex: 0 0 200px; /* Fixed width: 200px (won't shrink/grow) */
              min-width: 180px; /* Minimum width (prevents squishing) */">
    <img src="assets/images/muyang-profile.jpg" 
         alt="Muyang Lu Profile Picture" 
         width="100%" /* Fills the 200px column (image size) */
         height="auto" /* Maintains aspect ratio */
         style="border-radius: 8px; 
                box-shadow: 0 2px 5px rgba(0,0,0,0.1);
                display: block; /* Fixes alignment bugs */">
  </div>

  <!-- Bio Text (RIGHT column) -->
  <div style="flex: 1; /* Takes remaining space (grows to fill width) */
              min-width: 300px; /* Wraps to below image on mobile < 300px */
              align-self: flex-start; /* Aligns text to top of image */">
    Muyang’s research focuses on developing theoretical and statistical tools for macroecological studies. His work centers on niche and species distribution modeling, metacommunity dynamics, and the impacts of climate change on biodiversity.
  </div>
</div>
