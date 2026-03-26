---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a postdoctoral research scientist in the [Westervelt Aerosol Group](https://aerosol.ldeo.columbia.edu) at the Lamont-Doherty Earth Observatory, Columbia University. My research focuses on building machine/deep learning models to estimate air pollutants using satellite-derived features and weather reanalysis parameters, validated with ground-level sensors across sub-Saharan Africa. I further leverage these datasets to investigate health impacts of air pollution to support effective local policymaking.

I earned my Ph.D. in Mechanical Engineering from Carnegie Mellon University, where I worked with Prof. Albert Presto on developing low-cost techniques to measure atmospheric particulate matter and identifying emission sources from low-cost sensor networks. I also built a deep learning forecast model for PM2.5 over Pittsburgh using features from NASA's [GEOS-CF](https://gmao.gsfc.nasa.gov/weather_prediction/GEOS-CF/) and a spatially deployed low-cost sensor network.

I hold an M.Phil. and M.Sc. from the Hong Kong University of Science and Technology and a B.Tech. in Civil Engineering from the Indian Institute of Technology Delhi.

# 🔥 News

<style>
  .scrollable {
    max-height: 260px;
    overflow-y: scroll;
  }
</style>

<div class="scrollable">
  <ul>
    <li><strong>2025.12</strong>: Presented research in the NASA Health and Air Quality (HAQ) session at <strong>AGU 2025</strong> in New Orleans, Louisiana.</li>
    <li><strong>2025.06</strong>: Presented at the <a href="https://www.spartan-network.org/2025">CAMS-Net and SPARTAN meeting</a> hosted at Washington University in St. Louis.</li>
    <li><strong>2025.05</strong>: Attended the <a href="https://cimes.princeton.edu/princeton-university-geophysical-fluid-dynamics-laboratory-global-km-scale-hackathon-0">WCRP Global km-Scale Hackathon</a> at GFDL, Princeton University.</li>
    <li><strong>2025.01</strong>: Team El Ninos won <strong>1st place</strong> at the LEAP Hackathon "Harnessing Machine Learning to Improve Subseasonal-to-Seasonal Climate Predictions" at Columbia University.</li>
    <li><strong>2022.08</strong>: Awarded the prestigious <a href="https://engineering.cmu.edu/news-events/news/2023/04/12-dowd-fellows.html">Dowd Fellowship</a> by the School of Engineering at Carnegie Mellon University.</li>
  </ul>
</div>

# 🔬 Research Interests

I am broadly interested in the application of image processing and machine learning on remote sensing datasets, atmospheric simulations, and investigating health impacts from air pollution.

<img src="images/ResearchInterests.png" alt="Research Interests" style="width:100%; height:auto; margin-top:15px; border-radius:6px;">

# 📝 Publications

<p style="margin-top:5px; margin-bottom:15px; font-size: 14px; color: #555;"><em>* represents corresponding author</em></p>

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Dataset · Zenodo</div><img src='images/Gridded_PM25_Ghana_2025.png' alt="Gridded PM2.5 Ghana" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*[Dataset] Gridded Daily PM2.5 at 1 km x 1 km Resolution from 2005-2024: Ghana*

**Abhishek Anand\***, Joe Amooli, Daniel Westervelt

[**Dataset (Zenodo)**](https://doi.org/10.5281/zenodo.17920004) \| [**GRASP Project**](https://grasp.ldeo.columbia.edu)

This dataset provides daily estimates of surface PM2.5 concentrations across Ghana at 1 km x 1 km resolution, integrating satellite observations, ground-level monitors, and machine learning over 20 years (2005-2024).

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review · Scientific Reports</div><img src='images/2025_CongestionPricinginNYC.png' alt="NYC Congestion Pricing" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Variable Short-Term Air Quality Impacts of New York City's Congestion Pricing Policy*

Polina M. Goldberg, **Abhishek Anand**, Daniel Westervelt\*

[**Preprint**](https://www.researchsquare.com/article/rs-8158429/v1)

Using a difference-in-differences analysis, we assess the short-term impact of NYC's Central Business District Tolling Program (CBDTP) on PM2.5 and NO2 across all five boroughs using NYCCAS monitors and satellite observations.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ES&T Air · 2025</div><img src='images/2025_GriddedPM_WestAfrica.png' alt="PM2.5 West Africa" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Twenty Years of High Spatiotemporal Resolution Estimates of Daily PM2.5 in West Africa Using Satellite Data, Surface Monitors, and Machine Learning*

Daniel Westervelt\*, Joe Adabouk Amooli, **Abhishek Anand**

[**Paper**](https://pubs.acs.org/doi/10.1021/acsestair.4c00366)

We develop machine/deep learning models using satellite-derived and weather reanalysis parameters to estimate daily PM2.5 for Ghana at 1 km resolution over 2005-2024, validated against an extensive surface monitoring network.

</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Environment International · 2024</div><img src='images/Anand_Combining_google_EnvironmentalInternational_2024.jpg' alt="Google Traffic Deep Learning" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Combining Google Traffic Map with Deep Learning Model to Predict Street-Level Traffic-Related Air Pollutants in a Complex Urban Environment*

Peng Wei, Song Hao\*, Yuan Shi\*, **Abhishek Anand**, Ya Wang, Mengyuan Chu, Zhi Ning\*

[**Paper**](https://www.sciencedirect.com/science/article/pii/S0160412024005786)

We built a deep learning model to predict fine-scale NOx from traffic at street-level, combining data from mobile air quality sensors on buses with crowd-sourced Google real-time traffic status.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ES&T · 2024</div><img src='images/Anand_BCfromBAM_Africa.jpeg' alt="Black Carbon Africa" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Low-Cost Hourly Ambient Black Carbon Measurements at Multiple Cities in Africa*

**Abhishek Anand**, N'Datchoh Evelyne Toure, Julien Bahino, ..., Albert A. Presto\*

[**Paper**](https://pubs.acs.org/doi/full/10.1021/acs.est.4c02297)

We applied the image processing method from Anand et al. (2023) to used filter tapes from Beta Attenuation Monitors (BAMs) to measure atmospheric black carbon in African cities.

</div>
</div>

## 2023

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ES: Atmospheres · 2023</div><img src='images/Anand_BCfromBAM.jpg' alt="Black Carbon BAM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Estimation of Hourly Black Carbon Aerosol Concentrations from Glass Fiber Filter Tapes Using Image Reflectance-Based Method*

**Abhishek Anand**, Suryaprakash Kompalli, Eniola Ajiboyec, Albert A. Presto\*

[**Paper**](https://pubs.rsc.org/en/content/articlelanding/2023/ea/d2ea00166g) \| [**Processing Code**](data/image_bc.zip) \| [**Streamlit App**](data/image_bc_streamlit.zip) \| [**Instructions**](data/Run%20instructions%20for%20CV-based%20BC.pdf) \| [**Video**](https://youtu.be/DcCZJkAa9ew)

We deployed computer vision to build an image processing method to estimate atmospheric black carbon from particulate deposits on BAM filter tapes.

</div>
</div>

## 2021

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Environmental Pollution · 2021</div><img src='images/Peng_Determination_2021.jpg' alt="Traffic Emission" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Determination of Local Traffic Emission and Non-Local Background Source Contribution to On-Road Air Pollution Using Fixed-Route Mobile Air Sensor Network*

Peng Wei, Peter Brimblecombe, Fenhuan Yang, **Abhishek Anand**, Yang Xing, Li Sun, Yuxi Sun, Mengyuan Chu, Zhi Ning\*

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0269749121016377)

We applied wavelet analysis and lowest percentile methods to quantify contributions of traffic-related emissions to on-road gaseous and particulate levels.

</div>
</div>

## 2020

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sci. Total Environment · 2020</div><img src='images/Anand_Protocol_2020.jpg' alt="Drone Ship Fuel" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Protocol Development for Real-Time Ship Fuel Sulfur Content Determination Using Drone-Based Plume Sniffing Microsensor System*

**Abhishek Anand**, Peng Wei, Nirmal Kumar Gali, ..., Zhi Ning\*

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0048969720344144)

We developed an innovative solution for remotely measuring sulfur content in ship fuels from stack emissions using low-cost sensors on a drone, aimed at effective SO2 emissions policy enforcement.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Atmospheric Environment · 2020</div><img src='images/Peng_Development_2020.jpg' alt="NO2 Sensor Correction" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Development and Evaluation of a Robust Temperature Sensitive Algorithm for Long-Term NO2 Gas Sensor Network Data Correction*

Peng Wei, Li Sun, **Abhishek Anand**, Qing Zhang, Zong Huixin, Zhiqiang Deng, Ying Wang, Zhi Ning\*

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S1352231020302466)

We propose a novel Temperature Look-Up (TLU) model for NO2 gas sensor outputs in long-term applications, showing improved performance over existing ML and MLR correction methods.

</div>
</div>

# 🏆 Honors and Awards

- **Winner**, Hackathon on Applying Machine Learning for Subseasonal-to-Seasonal Climate Predictions, LEAP, Columbia University &nbsp;&nbsp;&nbsp; 2025
- **Travel Grant**, American Association for Aerosol Research (AAAR) Conference &nbsp;&nbsp;&nbsp; 2023
- **Philip and Marsha Dowd Fellowship**, Carnegie Mellon University (~$100,000 in tuition and stipend) &nbsp;&nbsp;&nbsp; 2022–2023
- **Milton Shaw Ph.D. Research Award**, Department of Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; 2022
- **Accepted Proposal**: Climate School Summer Internship Funding Program, Columbia University ($6,000) &nbsp;&nbsp;&nbsp; 2025
- **Postgraduate Studentship** for M.Phil. study, HKUST &nbsp;&nbsp;&nbsp; 2018–2020
- **HKUST Awardee**, 8th Global Young Scientists Summit, National Research Foundation, Prime Minister's Office, Singapore &nbsp;&nbsp;&nbsp; 2020
- **University Grants Committee Research Travel Grant**, HKUST &nbsp;&nbsp;&nbsp; 2019
- **Division of Environment and Sustainability Research Travel Grant**, HKUST &nbsp;&nbsp;&nbsp; 2019
- **Hong Kong Government Innovation and Technology Fund Internship Award** &nbsp;&nbsp;&nbsp; 2018
- **M.Sc. Excellent Student Scholarship**, School of Engineering, HKUST &nbsp;&nbsp;&nbsp; 2017
- **Champion Award**, BESTo Camp, HKUST Entrepreneurship Center &nbsp;&nbsp;&nbsp; 2017
- **Entrance Scholarship**, School of Engineering, HKUST &nbsp;&nbsp;&nbsp; 2016
- **Ministry of Human Resources Development Scholarship**, IIT Delhi (tuition for 4 years of undergraduate studies) &nbsp;&nbsp;&nbsp; 2011–2015

# 🎓 Education

- **Ph.D.**, Mechanical Engineering, Carnegie Mellon University, Pittsburgh, PA &nbsp;&nbsp;&nbsp; *May 2024*
  - Advisor: Prof. Albert Presto
- **M.Phil.**, Environmental Science, Policy and Management, Hong Kong University of Science and Technology &nbsp;&nbsp;&nbsp; *August 2020*
- **M.Sc.**, Environmental Engineering and Management, Hong Kong University of Science and Technology &nbsp;&nbsp;&nbsp; *May 2017*
- **B.Tech.**, Civil Engineering, Indian Institute of Technology Delhi, New Delhi, India &nbsp;&nbsp;&nbsp; *May 2015*

# 🎤 Invited Talks

- **GRAPHS Manuscript Series**, Columbia University, NY &nbsp;&nbsp;&nbsp; *December 2025*
  Mapping Two Decades of Daily High-Resolution PM₂.₅ Data in Ghana Using Machine Learning.

- **Geochemistry Division**, Columbia University, NY &nbsp;&nbsp;&nbsp; *October 2025*
  Atmospheric Black Carbon Measurements by Applying Image Processing Method on Filter Tapes.

- **Department of Civil Engineering**, University of Illinois Urbana-Champaign, IL &nbsp;&nbsp;&nbsp; *October 2025*
  Leveraging Satellite Measurements, Surface Monitors, and Machine Learning for Generating 20 Years of High-Resolution Daily PM₂.₅ in Ghana.

- **SPARTAN & CAMS-Net Joint Meeting**, Washington University in St. Louis, MO &nbsp;&nbsp;&nbsp; *June 2025*
  Two Decades of High-Resolution Daily PM₂.₅ in Ghana: A Machine Learning Approach.

- **Lamont 75th Mini-Symposium: The Data Driven Discovery**, Columbia University, NY &nbsp;&nbsp;&nbsp; *May 2025*
  Leveraging Satellite Measurements to Build Machine Learning Models for Estimating 20 Years of High-Resolution Gridded PM₂.₅ for Ghana.

- **Air Sensors International Conference**, Riverside, CA &nbsp;&nbsp;&nbsp; *October 2024*
  Low-cost methods for measurement of PM₂.₅ composition at African cities by exploiting existing Beta Attenuation Monitors.

# 🏫 Teaching

**Guest Lecture — Air Pollution & Measuring the Environment**, Columbia University &nbsp;&nbsp;&nbsp; *November 2025*
Introduced principles of remote sensing and tools for monitoring air quality, including accessing, visualizing, and interpreting satellite-derived pollution datasets from NASA and ESA.

**Future Faculty Career Program**, Carnegie Mellon University &nbsp;&nbsp;&nbsp; *2020–2024*
Designed to help early career researchers develop their teaching skills for a faculty career.

**Teaching Assistant**, Carnegie Mellon University & HKUST
- Renewable Energy Engineering – CMU &nbsp;&nbsp;&nbsp; Spring 2023
- Fluid Mechanics – CMU &nbsp;&nbsp;&nbsp; Spring 2022
- GIS for Environmental Professionals – HKUST &nbsp;&nbsp;&nbsp; Fall 2019
- Carbon Emission Trading – HKUST &nbsp;&nbsp;&nbsp; Spring 2019

**Peer Tutor for Undergraduate Students**, CMU &nbsp;&nbsp;&nbsp; *2022–2023*
Physics I & II, Calculus, Differential Equations.

**Student Mentoring**

*Undergraduate Research Mentor*
- Polina Goldberg, Data Science, Columbia University &nbsp;&nbsp;&nbsp; Summer 2025–Present
- Elsevar Zeynalov, Data Science, Columbia University &nbsp;&nbsp;&nbsp; Summer 2025
- Ria Sharma, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Summer 2023
- Jordan Petzold, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Summer 2023
- Jocelyn Kiefel, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Summer 2023
- Shaborn Leggette, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Summer 2023
- Max Labovitz, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Summer 2022

*Graduate Research Mentor*
- Sizhou Su, Master's student, Columbia University &nbsp;&nbsp;&nbsp; Summer 2025–Present
- Aziz Bhetasiwala, Master's student, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Fall 2023–Summer 2024
- Ria Sharma, Master's student, Mechanical Engineering, CMU &nbsp;&nbsp;&nbsp; Fall 2023

# 🤝 Service

**Session Chair**, AAAR: Advancing Aerosol Science Through Data Analysis &nbsp;&nbsp;&nbsp; *October 2025*

**Panel Discussion**, Spartan and CAMS-Net Meeting: Low-Cost Monitoring of Atmospheric Particulate Matter &nbsp;&nbsp;&nbsp; *June 2025*

**Coordinator**, Ocean and Climate Physics Department Seminar, Columbia University &nbsp;&nbsp;&nbsp; *2025–2026*

**Core Representative**, Postdoc/ARS Hardship Support Fund, Columbia University &nbsp;&nbsp;&nbsp; *2025–Present*

**President**, AAAR Student Chapter, Carnegie Mellon University &nbsp;&nbsp;&nbsp; *2023–2024*

**Coordinator**, Center for Atmospheric Particle Studies Seminar, Carnegie Mellon University &nbsp;&nbsp;&nbsp; *2022–2023*

**Core Committee Member**, CAPS Laboratory, Carnegie Mellon University &nbsp;&nbsp;&nbsp; *2021–2022*

**Reviewer** — Geoscientific Model Development, Environmental Science & Technology Air, Environment International, Scientific Reports, Environmental Science and Pollution Research &nbsp;&nbsp;&nbsp; *2023–Present*
# 📸 Events

<p style="margin-top: 10px;">
  <strong>December 2025</strong> — Presented research in the NASA Health and Air Quality (HAQ) session at <strong>AGU 2025</strong>, New Orleans, Louisiana.<br>
  <img src="images/Event_Images/AGU25_HAQ_Poster_All.jpg" alt="AGU 2025" style="width:85%; height:auto; margin-top:12px; border-radius:6px;">
</p>

<p style="margin-top: 30px;">
  <strong>June 2025</strong> — Presented at the <a href="https://www.spartan-network.org/2025">CAMS-Net and SPARTAN meeting</a> at Washington University in St. Louis.<br>
  <img src="images/Event_Images/2025_Spartan_CAMSNet_WUSTL.jpg" alt="SPARTAN CAMS-Net WUSTL" style="width:85%; height:auto; margin-top:12px; border-radius:6px;">
</p>

<p style="margin-top: 30px;">
  <strong>May 2025</strong> — Attended the <a href="https://cimes.princeton.edu/princeton-university-geophysical-fluid-dynamics-laboratory-global-km-scale-hackathon-0">WCRP Global km-Scale Hackathon</a> at GFDL, Princeton University.<br>
  <img src="images/Event_Images/GFDL_WCRP_Hackathon_May2025.jpg" alt="WCRP Hackathon GFDL" style="width:85%; height:auto; margin-top:12px; border-radius:6px;">
</p>

<p style="margin-top: 30px;">
  <strong>January 2025</strong> — Team El Ninos won <strong>1st place</strong> at the LEAP Hackathon "Harnessing Machine Learning to Improve Subseasonal-to-Seasonal Climate Predictions" at Columbia University.<br>
  <img src="images/Event_Images/LEAP_Hackathon.png" alt="LEAP Hackathon" style="width:85%; height:auto; margin-top:12px; border-radius:6px;">
</p>

<p style="margin-top: 30px;">
  <strong>August 2022</strong> — Awarded the prestigious <a href="https://engineering.cmu.edu/news-events/news/2023/04/12-dowd-fellows.html">Dowd Fellowship</a> by the School of Engineering at Carnegie Mellon University.<br>
  <img src="images/Event_Images/dowd_fellowship_2022.png" alt="Dowd Fellowship" style="width:85%; height:auto; margin-top:12px; border-radius:6px;">
</p>

