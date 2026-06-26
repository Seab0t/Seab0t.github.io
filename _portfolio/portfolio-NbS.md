---
title: "A Decision Support Tool for Enhancing Resilience to Urban Overheating with Nature-Based Solutions"
collection: portfolio
layout: portfolio-item
order: 2
header:
  teaser: https://Seab0t.github.io/images/NbS.png
share: false
author_profile: false
project_role: "Lead Student Researcher"
github_link: "https://github.com/Seab0t/NbS_tool"
project_link: "https://bilab.engineering.nyu.edu/projects/cv-based-defects"
project_tech: "Python, Scrapy, Computer Vision, Deep Learning, NLP"
project_time: "May 2025 - Present"
gallery_description: How can we optimize urban canopy expansion to mitigate thermal stress in NYC neighborhoods facing the highest heat risk?
---
<div style="border-left: 3px solid #e2e8f0; padding-left: 15px; margin-bottom: 30px; color: #64748b; font-size: 0.9rem; line-height: 1.6;">
  <strong>Project Sponsors:</strong><br>
  Prof. Constantinos Cartalis, Dr. Ilias Agathangelidis, and Dr. Kostas Philippopoulos <br>
  <em>National and Kapodistrian University of Athens (Greece)</em>
</div>

<div style="text-align: center; margin-top: 1rem; margin-bottom: 3rem;">
  <a href="https://Seab0t.github.io/files/Poster_NbS.pdf" target="_blank" title="Click to view full PDF poster">
    <img src="https://Seab0t.github.io/images/NbS_Thumb.png" alt="Project Poster" style="border: 1px solid #eaeaea; box-shadow: 0 8px 24px rgba(0,0,0,0.06); border-radius: 8px; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.02)'" onmouseout="this.style.transform='scale(1)'">
  </a>
</div>
New York City faces highly unequal heat risks across its neighborhoods. While green infrastructure is a proven cooling strategy, optimizing its deployment for spatial equity and long-term effectiveness under future climate scenarios remains a critical challenge. This project integrates downscaled satellite imagery and microclimate simulations to assess neighborhood-level heat risk and quantify the cooling efficacy of different urban canopy expansion schemes.

### Methodology
<div style="border-left: 3px solid #1a1a1a; padding-left: 20px; margin-bottom: 35px;">
  <h4 style="margin: 0 0 6px 0; font-size: 1.15rem; font-weight: 600; color: #000;">1. Heat Risk Identification</h4>
  <p style="margin: 0 0 10px 0; font-size: 1.05rem; color: #555; line-height: 1.5;">
    Calculated neighborhood-level heat risk across NYC by integrating downscaled land surface temperature, land cover and socioeconomic indicators.
  </p>
  <ul style="font-size: 1.05rem; color: #333; margin: 0 0 16px 0; padding-left: 20px; line-height: 1.6;">
    <li> <a href="https://github.com/Seab0t/Sentinel3_Download_Process_Python" target="_blank" style="display: inline-flex; align-items: center; gap: 6px; font-size: 1.05rem; font-weight: 500; color: #1a1a1a; text-decoration: none; border: 1px solid #ccc; padding: 4px 12px; border-radius: 4px; transition: all 0.2s;" onmouseover="this.style.borderColor='#000'; this.style.backgroundColor='#f9f9f9'" onmouseout="this.style.borderColor='#ccc'; this.style.backgroundColor='transparent'">
    <svg style="width:16px; height:16px; fill:currentColor;" viewBox="0 0 24 24"><path d="M12 2C6.477 2 2 6.477 2 12c0 4.42 2.865 8.166 6.839 9.489.5.092.682-.217.682-.482 0-.237-.008-.866-.013-1.7-2.782.603-3.369-1.34-3.369-1.34-.454-1.156-1.11-1.462-1.11-1.462-.908-.62.069-.608.069-.608 1.003.07 1.531 1.03 1.531 1.03.892 1.529 2.341 1.087 2.91.831.092-.646.35-1.086.636-1.336-2.22-.253-4.555-1.11-4.555-4.943 0-1.091.39-1.984 1.03-2.682-.103-.253-.447-1.27.098-2.646 0 0 .84-.269 2.75 1.025A9.578 9.578 0 0112 6.836c.85.004 1.705.114 2.504.336 1.909-1.294 2.747-1.025 2.747-1.025.546 1.376.202 2.394.1 2.646.64.699 1.026 1.591 1.026 2.682 0 3.841-2.337 4.687-4.565 4.935.359.309.678.919.678 1.852 0 1.336-.012 2.415-.012 2.743 0 .267.18.578.688.48C19.138 20.161 22 16.416 22 12c0-5.523-4.477-10-10-10z"/></svg>
    Automated Sentinel-3 thermal data processing
  </a></li>
    <li><b>LST Downscaling:</b> Pixel Block Intensity Modulation.</li>
  </ul>
  
</div>

<div style="border-left: 3px solid #1a1a1a; padding-left: 20px; margin-bottom: 30px;">
  <h4 style="margin: 0 0 6px 0; font-size: 1.15rem; font-weight: 600; color: #000;">2. Microclimate Simulation</h4>
  <p style="margin: 0 0 10px 0; font-size: 1.05rem; color: #555; line-height: 1.5;">
    Conducted cooling simulations for the top 5 high-risk NYC neighborhoods.
  </p>
  <ul style="font-size: 1.05rem; color: #333; margin: 0; padding-left: 20px; line-height: 1.6;">
    <li><b>Climate Scenarios:</b> Compared baseline (2017-2020) against future high-emission projections (SSP5-RCP8.5, 2020-2039).</li>
    <li><b>NbS Intervention:</b> Modeled a 20% urban tree canopy expansion.</li>
  </ul>
</div>

### Beyond The Project
#### LST Downscaling
For this project, a simple statistical model was sufficient because our primary goal was comparing relative heat across neighborhoods within a single city. However, for broader ecological monitoring or urban thermal analysis, achieving high spatiotemporal resolution is highly valuable. Multi-sensor data fusion, cloud interference, model sensitivity to spatial scaling, chose of auxiliary datasets and physical constraints in deep learning, all remain challenges for LST downscaling.

#### Visual Thermal Perception & Human Behavior
- Beyond the absolute air temperature, how do perceived greenery, shadows, and even crowd density shape our cognitive thermal comfort?

- Under varying environmental conditions, such as a sudden heatwave or canopy expansion, how do pedestrian traffic flows and routing decisions dynamically adapt?