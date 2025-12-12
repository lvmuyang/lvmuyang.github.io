---
title: "Research"
permalink: "/research/"
layout: page
---

<!-- Global Style for Links (Consistent Across Sections + Dark Mode Support) -->
<style>
  .research-link {
    color: #2c3e50 !important;
    text-decoration: underline !important;
  }
  /* Dark mode override for hyperlinks */
  @media (prefers-color-scheme: dark) {
    .research-link {
      color: white !important; /* White text for links in dark mode */
      text-decoration: underline !important; /* Keep underline for visibility */
    }
    /* Dark mode for all section titles (higher contrast) */
    .niche-title {
      color: #add8e6 !important; /* Lighter blue for Niche modeling */
    }
    .metacomm-title {
      color: #90ee90 !important; /* Pale green for Meta-community (dark mode) */
    }
    .extinction-title {
      color: #f08080 !important; /* Pale red for Extinction risk (dark mode) */
    }
  }
  /* Optional: Mobile responsiveness (image full-width on small screens) */
  @media (max-width: 600px) {
    .research-img {
      float: none !important;
      width: 100% !important;
      margin-left: 0 !important;
      margin-right: 0 !important;
      margin-bottom: 1rem !important;
    }
  }
</style>

<!-- Niche modeling (Light Blue Title + Left Image + Text Wrap) -->
<h2 class="niche-title" style="color: #87ceeb !important; margin-top: 2rem !important;">Niche modeling</h2>
<div style="max-width: 1000px !important; 
            margin: 0 auto !important; 
            padding: 0 1rem !important; 
            line-height: 1.6 !important;
            font-size: 16px !important;">

  <img 
    src="https://lvmuyang.github.io/files/niche_modeling.svg"
    alt="Niche modeling" 
    class="research-img"
    style="float: left !important; 
           width: 200px !important; 
           min-width: 180px !important;
           margin-right: 2rem !important; 
           margin-bottom: 1rem !important;
           border-radius: 8px !important;
           box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
           border: none !important;
           height: auto !important;">

  The concept of the niche (i.e. the environmental conditions that allow a species' persistence) is almost as old as the field of ecology itself. 
  Despite the normal unification and conceptual elegance of the idea, empirically measuring the niche is challenging.<br><br>

  I show how Hutchinson's hypervolume can be measured using <a href="http://lvmuyang.github.io/files/MEE_2021.pdf" target="_blank" class="research-link">a probabilistic framework</a> that allows partitioning niche variation into ecologically meaningful components.<br><br>

  The quantification of the environmental niche depends on the spatial grain over which it is measured. We develop <a href="http://lvmuyang.github.io/files/TREE_2023.pdf" target="_blank" class="research-link">a conceptual framework</a> to demonstrate how the scale-dependence of niche geometry can be predicted from key ecological attributes.<br><br>

  While understanding intraspecific niche variation is crucial for forecasting biodiversity change, the mathematical link between the species niche and individual niches remains elusive. I show how to <a href="http://lvmuyang.github.io/files/PNAS_2025.pdf" target="_blank" class="research-link">scale from individual niches to the species niche</a>, opening up new opportunities to investigate ecological and evolutionary topics.<br><br>

  <div style="clear: both !important;"></div>
</div>

<!-- Meta-community (Light Green Title + Right Image + Text Wrap) -->
<h2 class="metacomm-title" style="color: #90ee90 !important; margin-top: 3rem !important;">Meta-community</h2>
<div style="max-width: 1000px !important; 
            margin: 0 auto !important; 
            padding: 0 1rem !important; 
            line-height: 1.6 !important;
            font-size: 16px !important;">

  <img 
    src="https://lvmuyang.github.io/files/meta-community.svg"
    alt="Meta-community" 
    class="research-img"
    style="float: right !important; 
           width: 200px !important; 
           min-width: 180px !important;
           margin-left: 2rem !important; 
           margin-bottom: 1rem !important;
           border-radius: 8px !important;
           box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
           border: none !important;
           height: auto !important;">

  The theory of island biogeography (TIB) proposed by R. MacArthur and E.O. Wilson in the 1960s is one of the cornerstones of modern ecology. Yet, a key element of community ecology—beta diversity patterns (variation in community composition)—is missing from their theory. I derive <a href="http://lvmuyang.github.io/files/AmNat_2019.pdf" target="_blank" class="research-link">beta diversity patterns from the TIB</a> and show how they are linked to extinction, colonization, and the size of the species pool. Combining the TIB and the meta-population model, I further demonstrate that meta-community dynamics could lead to <a href="http://lvmuyang.github.io/files/Ecog_2021.pdf" target="_blank" class="research-link">complex response of beta diversity to dispersal</a>.<br><br>

  Traditional beta diversity metrics do not account for species associations, which could lead to biased inference of community assembly. We took <a href="http://lvmuyang.github.io/files/EcoMon_2025.pdf" target="_blank" class="research-link">a geometric approach to measure beta diversity</a> and show how it offers a more holistic view of metacommunity dynamics.<br><br>

  <div style="clear: both !important;"></div>
</div>

<!-- Extinction risk (Light Red Title + Left Image + Text Wrap) -->
<h2 class="extinction-title" style="color: #f08080 !important; margin-top: 3rem !important;">Extinction risk</h2>
<div style="max-width: 1000px !important; 
            margin: 0 auto !important; 
            padding: 0 1rem !important; 
            line-height: 1.6 !important;
            font-size: 16px !important;">

  <img 
    src="https://lvmuyang.github.io/files/extinction_risk.svg"
    alt="Extinction risk" 
    class="research-img"
    style="float: left !important; 
           width: 200px !important; 
           min-width: 180px !important;
           margin-right: 2rem !important; 
           margin-bottom: 1rem !important;
           border-radius: 8px !important;
           box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
           border: none !important;
           height: auto !important;">

  Climate change poses a severe threat to thousands of species. Predicting species' extinction risk is critical to guiding biodiversity conservation efforts. Using <a href="http://lvmuyang.github.io/files/GCB_2025.pdf" target="_blank" class="research-link">a novel climate change vulnerability measure</a>, we show that coarse-grain analysis can seriously underestimate the extinction risk of tropical species.<br><br>
  We further investigate how the <a href="http://lvmuyang.github.io/files/ProcB_2025.pdf" target="_blank" class="research-link">timings of extreme climate exposure</a> are shaped by species' distribution and ecological traits.<br><br>

  <div style="clear: both !important;"></div>
</div>
