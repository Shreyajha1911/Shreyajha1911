<div align="center">
<svg viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg" width="900">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="40%" style="stop-color:#111a14"/>
      <stop offset="100%" style="stop-color:#0d1f0f"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ff88;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00ff88;stop-opacity:0.8"/>
      <stop offset="70%" style="stop-color:#00cc66;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#00cc66;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <!-- Background -->
  <rect width="900" height="220" fill="url(#bgGrad)"/>
  <!-- Grid lines - circuit board feel -->
  <g opacity="0.07" stroke="#00ff88" stroke-width="0.5">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="80" x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="0" y1="200" x2="900" y2="200"/>
    <line x1="100" y1="0" x2="100" y2="220"/>
    <line x1="200" y1="0" x2="200" y2="220"/>
    <line x1="300" y1="0" x2="300" y2="220"/>
    <line x1="450" y1="0" x2="450" y2="220"/>
    <line x1="600" y1="0" x2="600" y2="220"/>
    <line x1="700" y1="0" x2="700" y2="220"/>
    <line x1="800" y1="0" x2="800" y2="220"/>
  </g>
  <!-- Circuit dots at intersections -->
  <g fill="#00ff88" opacity="0.15">
    <circle cx="100" cy="40" r="2"/><circle cx="200" cy="40" r="2"/><circle cx="300" cy="40" r="2"/>
    <circle cx="600" cy="40" r="2"/><circle cx="700" cy="40" r="2"/><circle cx="800" cy="40" r="2"/>
    <circle cx="100" cy="80" r="2"/><circle cx="800" cy="80" r="2"/>
    <circle cx="100" cy="160" r="2"/><circle cx="200" cy="160" r="2"/>
    <circle cx="700" cy="160" r="2"/><circle cx="800" cy="160" r="2"/>
    <circle cx="100" cy="200" r="2"/><circle cx="300" cy="200" r="2"/>
    <circle cx="600" cy="200" r="2"/><circle cx="800" cy="200" r="2"/>
  </g>
  <!-- Glowing horizontal accent line -->
  <line x1="0" y1="110" x2="900" y2="110" stroke="url(#lineGrad)" stroke-width="1.5"/>
  <!-- Corner brackets -->
  <g stroke="#00ff88" stroke-width="1.5" fill="none" opacity="0.6">
    <path d="M20,15 L20,5 L30,5"/><path d="M870,5 L880,5 L880,15"/>
    <path d="M20,205 L20,215 L30,215"/><path d="M870,215 L880,215 L880,205"/>
  </g>
  <!-- Small data pulse dots on the accent line -->
  <g filter="url(#glow)">
    <circle cx="180" cy="110" r="3" fill="#00ff88" opacity="0.9"/>
    <circle cx="450" cy="110" r="4" fill="#00ff88" opacity="1"/>
    <circle cx="720" cy="110" r="3" fill="#00ff88" opacity="0.9"/>
  </g>
  <!-- Name -->
<text x="450" y="75" font-family="'Courier New', monospace" font-size="48" font-weight="bold"
 fill="#ffffff" text-anchor="middle" filter="url(#glow)" letter-spacing="4">SHREYA JHA</text>
  <!-- Subtitle -->
<text x="450" y="148" font-family="'Courier New', monospace" font-size="14"
 fill="#00ff88" text-anchor="middle" letter-spacing="3" opacity="0.9">
DATA SCIENCE  ·  ANALYTICS  ·  IoT  ·  ML PIPELINES
</text>
  <!-- Tagline -->
<text x="450" y="182" font-family="'Courier New', monospace" font-size="11"
 fill="#4a9e6b" text-anchor="middle" font-style="italic" opacity="0.8">
// from hardware that senses the world to pipelines that make sense of it
</text>
</svg>
</div>

<div align="center">
MSc Business Analytics & Big Data · IE Business School, Madrid
Data Analyst  ·  Data Scientist  ·  Open to Roles in Europe
</div>

About Me
Electronics engineer turned data scientist. I spent my undergrad building IoT systems — sensors, microcontrollers, devices that stream live data to the cloud. Now I'm finishing my Master's at IE Business School in Madrid, working on everything from distributed Spark pipelines to sustainability analytics for national energy infrastructure.
I like problems that have real stakes. Grid capacity for EV rollouts, seismic risk zones, election results, retail revenue concentration — the kind of work where a bad analysis has actual consequences.

Tech Stack
<div align="center">
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
Show Image
</div>

Projects
🌍 Seismic Risk Intelligence Platform
End-to-end Spark pipeline processing USGS seismic data — NiFi ingestion, MinIO storage, K-means clustering for risk zone classification. Alaska risk index 0.854 vs California 0.764 — frequency alone is misleading.
Apache Spark · NiFi · MinIO · Python · K-Means

⚡ IE × Iberdrola Sustainability Datathon
Analysed Viesgo grid capacity across northern Spain to map EV charging infrastructure bottlenecks for the 2027 national rollout. Found 77% of substations have under 2 MW available capacity.
Python · GeoPandas · pyproj · Spark

👁️ VisionMate — IoT Assistive Mobility Stick
Smart blind stick with obstacle detection, wet surface warning, smoke detection, and live GPS tracking via ThingSpeak. Built on ESP32 + Arduino. Research paper submitted to Songklanakarin Journal of Science and Technology.
ESP32 · Arduino · ThingSpeak · GPS · Bluetooth · IoT

📊 Tata Online Retail — Revenue & Customer Analytics
Power BI dashboard revealing that high-value customers generate £8.7M — 90% of total revenue despite being 37% of the customer base. Built for the Tata Virtual Experience Programme.
Power BI · DAX · Excel

🗳️ Telangana Elections 2023 Dashboard
Interactive Power BI dashboard visualising MLA and MP election results across all Telangana constituencies. Built during internship at Hareesh IT Industries.
Power BI · SQL · Excel

🎾 Tennis ATP Match Prediction — MLOps Pipeline (Group · IE Business School)
Production-grade ML pipeline predicting ATP match outcomes. FastAPI + Streamlit deployed on Render. 95% better log loss than rank heuristic baseline. My contribution: W&B experiment tracking + model registry.
Python · FastAPI · Streamlit · W&B · Docker · sklearn

📈 S&P 500 Equity Selection Engine (Group · IE Business School)
Long-only cross-sectional alpha strategy using XGBoost + Random Forest with half-Kelly bet sizing. +7.40% total return vs S&P 500 +4.4% out-of-sample.
Python · XGBoost · Random Forest · sklearn

🏗️ KPMG Capstone (In Progress)
Final capstone project in collaboration with KPMG. Large-scale business data — goal is a client-ready deliverable. Updates soon.

GitHub Stats
<div align="center">
Show Image
Show Image
</div>

<div align="center">
📍 Madrid  ·  🎓 Graduating July 2026  ·  🌍 Open to roles in Ireland, Netherlands & beyond
<a href="https://linkedin.com/in/shreya-jha-a82605257/"><img src="https://img.shields.io/badge/LinkedIn-0d1f0f?style=for-the-badge&logo=linkedin&logoColor=00ff88"/></a>
<a href="mailto:shreya.jha@student.ie.edu"><img src="https://img.shields.io/badge/Email-0d1f0f?style=for-the-badge&logo=gmail&logoColor=00ff88"/></a>
</div>

