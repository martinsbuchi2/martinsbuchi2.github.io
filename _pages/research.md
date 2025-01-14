---
permalink: /research/
author_profile: true
type: page
classes: wide
layout: single
title: "Research"
header:
  overlay_image: /assets/images/research.jpg
  caption: Otamiri River, Southern Nigeria
---
# Research and Research Interest

My research interests focus on leveraging geospatial technologies, Earth Observation, and remote sensing to promote sustainability. I am particularly drawn to using spatial analysis, GeoAI and data integration to model ecosystem dynamics, support policy development, and drive impactful solutions for environmental challenges.

<head>
  <!-- <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Table with Read More/Less</title> -->
   <style>
    table {
      width: 100%;
      border-spacing: 10px;
    }
    .td-align {
      vertical-align: top;
      text-align: center;
      max-width: 500px;
      height: auto;
    }
    img {
      width: 100%;
      max-width: 500px;
      max-height: 300px;
      border-radius: 15px;
      border: 1px solid #000000;
      margin-bottom: 10px;
    }
    a {
      margin-bottom: 10px;
    }
    .hidden-content {
      display: none;
    }
     /* Paragraph text styling */
    .toggle-paragraph {
      font-size: 50px; /* Set the desired font size here */
      line-height: 1.6; /* Optional: Adjust line height for better readability */
      margin: 10px 0;
    }
    .toggle-button {
      cursor: pointer;
      text-decoration: underline;
    }

    /* Responsive Design */
    @media screen and (max-width: 768px) {
      table {
        display: block;
      }
      tr {
        display: block;
        margin-bottom: 20px;
      }
      td {
        display: block;
        width: 100%;
      }
    }
  </style>
</head>

<body>
<table>  
<tr>  
<td class="td-align"><img src="/assets/images/photosynthesis_CAS.png" alt="Image 1"/><br/>
      <a href="https://drive.google.com/file/d/125UMIJKCs6rYyxgpQzGqWOI_snqkqVII/view?usp=sharing">1. Effect of land use land cover changes on the rate of soil erosion in the Otamiri Watershed, Southern Nigeria</a><br/>
      <div class="paragraph-wrapper">
      <p class="toggle-paragraph">This study examines the impact of land use and land cover (LULC) changes on soil erosion rates within the Otamiri watershed spanning across Owerri to Rivers States, Southern, Nigeria. Using the Revised Universal Soil Loss Equation (RUSLE) integrated with remote sensing and GIS technologies, the research tracks LULC changes between 1996 and 2016. The findings indicate significant deforestation and land conversion, leading to increased soil erosion. This necessitates the implementation of sustainable land management practices to mitigate further degradation. <br />
      <br />
      <p> See <a href="https://drive.google.com/file/d/125UMIJKCs6rYyxgpQzGqWOI_snqkqVII/view?usp=sharing">Poster Presentation: </a> 2021 World Environment Day Celebration, themed: <italics>"Ecosystem Restoration"</italics></p></p></div>
</td>  
<td class="td-align"><img src="/assets/images/crop_irrigation.jpg" alt="Image 2"/><br/>
      <a href="https://drive.google.com/file/d/1vHLr9sQ9xq16wzPUQyQrtkBsTeU486GB/view?usp=sharing">2. GIS Approach to Site Suitability for Large-Scale Solar Farms in Osun East District, Nigeria</a><br/>
      <div class="paragraph-wrapper">
      <p class="toggle-paragraph">This study focuses on identifying optimal sites for large-scale solar farms within the Osun East District, Nigeria. It employs GIS and Analytic Hierarchical Process (AHP) to perform suitability analysis, identifying the most favorable locations based on environmental, social, and technical criteria. The study reveals that approximately 2.6% of the total area is highly suitable, potentially generating 3,470 MW of electricity, while moderately suitable areas could yield an additional 28,000 MW. The findings highlight the significant renewable energy potential in Osun East. <br />
      <br />
      <p> See <a href="https://drive.google.com/file/d/1vHLr9sQ9xq16wzPUQyQrtkBsTeU486GB/view?usp=sharing">Poster Presentation: </a> NASRDA 2018 GIS Day, themed: <italics>“Geospatial Technologies for National Development"</italics></p></p></div>
</td> 
</tr>


</table>
 <script>
    document.addEventListener("DOMContentLoaded", () => {
      const paragraphs = document.querySelectorAll(".toggle-paragraph");
      paragraphs.forEach(paragraph => {
        const words = paragraph.textContent.split(" ");
        if (words.length > 15) {
          const visibleContent = words.slice(0, 15).join(" ");
          const hiddenContent = words.slice(15).join(" ");
          paragraph.innerHTML = `
            ${visibleContent}
            <span class="hidden-content">${hiddenContent}</span>
            <span class="toggle-button" onclick="toggleContent(this)">Read More</span>
          `;
        }
      });
    });

    function toggleContent(button) {
      const hiddenContent = button.previousElementSibling;
      if (hiddenContent.style.display === "none") {
        hiddenContent.style.display = "inline";
        button.textContent = "Read Less";
      } else {
        hiddenContent.style.display = "none";
        button.textContent = "Read More";
      }
    }
  </script>
</body>

## Other Contributions


Through my involvement with INTEGRATION Consulting and the Rural Electrification Agency, I have contributed to various projects and initiatives, including but not limited to:
- 