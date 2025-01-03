---
permalink: /cv/
title: "CV"
author_profile: true
type: page
classes: wide
layout: single
header:
    overlay_image: /assets/images/header_photo_small.jpg
    caption: Checkout my CV!
---
## [Download CV](https://drive.google.com/file/d/1tkLFHEBAa-kUmDhZMFezwS8hv2tERq5d/view?usp=sharing) | [See the Europass format](https://drive.google.com/file/d/1nmYhALcjy6R9zKAfx3UoRwfOyfzvxdX6/view?usp=sharing)

### Education

`2012 - 2017`
B. Tech. in Environment (Geo-Environmental) Technology, [Federal University of Technology Owerri](https://futo.edu.gov)

`2023 - 2024`
Certificate Course in Software Engineering, [ALX Africa](https://www.alxafrica.com)

### Profesional Experience

* `2023-present`
Technical Assistant (on Geospatial Analysis) to the Executive Director, Technical Services, [Rural Electrification Agency of Nigeria](https://rea.gov.ng/) | `Abuja, Nigeria`

* `2022-2023`
National Expert - Geodata Consultant, [INTEGRATION Consulting Group](https://integration.org/environment-energy/) | `Remote`

* `2019-2022`
GIS Instructor, [Gpro Group](https://goldenpro.group/) | `Abuja, Nigeria`

* `2018-2019`
Graduate Intern, [Nasarawa Urban Development Board](https://nasarawastate.gov.ng/nasarawa-state-urban-development-board/) | `Nasarawa, Nigeria`

* `2017`
Research Intern, [National Space Research and Development Agency](https://central.nasrda.gov.ng/) | `Abuja, Nigeria`

### Grants and Awards

* `2019`
[Tony Elumelun Foundation](https://tefconnect.com/), TEF Entrepreurship Programme

* `2017`
Enugu State, Undergraduate Scholarship Award

* `2013 - 2016`
Federal Government of Nigeria, Undergraduate Scholarship

* `2013 - 2015`
MTN Foundation, Undergraduate Scholarship

### Volunteering, Community Service & Outreach

* `2022`
Energize Conference (GIZ Renewable Energy Career Fair)

* `2017 - date`
GIS Day Conference (NASRDA)

* `2017 - date`
World Environment Day Conference (FUTO)

### Networks and Membership

* `2024 – date`
[EO Africa Community](https://www.eoafrica-rd.org/eo-africa-community/) - African Framework for Research Innovation, Communities and Applications in Earth Observation

* `2024 – date`
[ESRI Young Professionals Network (YPN)](https://www.esri.com/en-us/about/ypn/overview)

* `2023 – date`
[ALX Africa and The ROOM Fellowship](https://www.alxafrica.com/alumni-community/)
* `2023 – date`
Student Energy Fellowship
* `2019 – date`
[Tony Elumelu Foundation (TEF)](https://tefconnect.com/)

* `2019 – date`
[The Young African Leaders Initiative (YALI)](https://yaliwestafrica.net/rlc/), Regional Leadership Center, West Africa - Accra

* `2016 – date`
[Geo-Information Society of Nigeria (GEOSON)](https://geoson.ng/become-a-member/)



<div id="theme-toggle" 
     style="position: fixed; top: 20px; right: 20px; z-index: 1000; cursor: pointer; font-size: 24px;" 
     onclick="toggleTheme()">
  <span id="toggle-icon">☀️</span>
</div>

<script>
  function toggleTheme() {
    const body = document.body;
    const icon = document.getElementById('toggle-icon');
    const isDark = body.classList.toggle('dark-theme');
    localStorage.setItem('theme', isDark ? 'dark' : 'light');
    icon.textContent = isDark ? '☀️' : '🌙';
  }

  (function() {
    const savedTheme = localStorage.getItem('theme') || 'dark';
    const body = document.body;
    const icon = document.getElementById('toggle-icon');
    if (savedTheme === 'dark') {
      body.classList.add('dark-theme');
      icon.textContent = '☀️';
    } else {
      icon.textContent = '🌙';
    }
  })();
</script>

<style>
body {
  background-color: white;
  color: black;
  transition: background-color 0.3s, color 0.3s;
}

body.dark-theme {
  background-color: #121212;
  color: white;
  transition: background-color 0.3s, color 0.3s;
}
</style>
