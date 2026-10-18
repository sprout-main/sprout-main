<div align="center">

# 🌱 Jake Carlo G. Mandi
### *Full-Stack Web Developer • Systems Architect*
<p align="center">
  <a href="https://github.com/sprout-main">
    <img src="https://img.shields.io/badge/GitHub-sprout--main-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile">
  </a>
  <a href="https://github.com/jakews2">
    <img src="https://img.shields.io/badge/GitHub-jakews2-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile">
  </a>
</p>

[![Status](https://img.shields.io/badge/Status-Building_%26_Shipping-7c3aed?style=flat-square&logo=rocket&logoColor=white)](#-featured-projects)
[![Live Project](https://img.shields.io/badge/SarakGIS-sarak.free.nf-10b981?style=flat-square&logo=leaflet&logoColor=white)](https://sarak.free.nf)
[![Education](https://img.shields.io/badge/BSIT-Data_Center_Colleges_of_The_Philippines-2563eb?style=flat-square&logo=googleclassroom&logoColor=white)](#-education--experience)
[![Email](https://img.shields.io/badge/Email-mandijakecarlog%40gmail.com-d97706?style=flat-square&logo=gmail&logoColor=white)](mailto:mandijakecarlog@gmail.com)

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=7C3AED&center=true&vCenter=true&width=700&lines=Full-Stack+Web+Developer;Creator+of+Sarak+(sarak.free.nf);Creator+of+Bayugo+Dental+Clinic+System;Laravel+%26+PHP+Motion+%7C+PostGresql+MariaDB+RBAC;Building+Practical+Digital+Solutions+%26+Clean+Systems" alt="Jake Carlo G. Mandi Typing SVG"/>
</p>

> *"Building practical, high-impact digital solutions and scalable architectures."*

<br/>

[💡 About Me](#-about-me) • [🚀 Featured Projects](#-featured-projects) • [🛠️ Technical Arsenal](#️-technical-arsenal) • [📊 GitHub Metrics](#-github-metrics) • [🎓 Experience & Education](#-education--experience) • [📫 Connect](#-connect--collaborate)

---

</div>

## 💡 About Me

I am an **Information Technology student (BSIT)** at **Data Center Colleges of The Philippines (Bangued, Abra)**, specializing in full-stack web development, spatial database engineering, and practical system architecture.

My development stack is grounded in **Laravel & PHP monoliths**, **MariaDB/MySQL spatial geometry**, **interactive Leaflet.js mapping**, and **responsive modern frontends**. I focus on architecting complete, reliable systems — from community geospatial directories with rigorous moderation pipelines to clinical scheduling platforms and zero-overhead static portfolios.

> [!NOTE]
> **Core Principle:** Build solutions that operate reliably under real-world constraints, enforcing data integrity through strict system invariants and intuitive user experiences.

---

## 🚀 Featured Projects

<div align="center">

### 🗺️ **Sarak — Bangued Community Spatial Atlas**
**Live Community Geospatial Directory & Open Data Platform**

[![Live Deployment](https://img.shields.io/badge/Live_Site-sarak.free.nf-10b981?style=for-the-badge&logo=googleearth&logoColor=white)](https://sarak.free.nf)
[![Laravel 11](https://img.shields.io/badge/Laravel_11-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://sarak.free.nf)
[![MariaDB Spatial](https://img.shields.io/badge/MariaDB_Spatial_GIS-003545?style=for-the-badge&logo=mariadb&logoColor=white)](https://sarak.free.nf)
[![Leaflet.js](https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white)](https://sarak.free.nf)

</div>

**Sarak** (`sarak.free.nf`) is an interactive spatial atlas and verified directory cataloging essential establishments — fast food chains, hospitals, pharmacies, groceries, coffee shops, and points of interest across **Bangued, Abra**.

- **Spatial Queries:** Leverages **MariaDB 10.4 Spatial Extensions** storing coordinates as `POINT` geometries (SRID 4326) with `MBRContains` bounding-box queries and `ST_Distance_Sphere` radial searches for high-performance interactive map pan/zoom.
- **Audited Moderation Architecture:** Residents submit new places and photos to an isolated moderation queue (`mod_queue`). Changes undergo side-by-side diff review before approval — guaranteeing *zero unapproved mutations ever touch public read endpoints*.
- **Automated Intake:** Custom artisan ingestion pipelines querying the **OSM Overpass API**, **Nominatim geocoding**, and official administrative boundary lists with automatic spatial deduplication.
- **Open Data & Analytics:** Automated GeoJSON (`/api/export.geojson`) and CSV (`/api/export.csv`) public data export, paired with an administrative coverage matrix across all barangays.

<p align="center">
  🌐 <strong>Explore Live:</strong> <a href="https://sarak.free.nf"><strong>sarak.free.nf</strong></a>
</p>

---

<table>
  <tr>

### 🦷 Bayugo Dental Clinic System
**Comprehensive Clinical Operations & Scheduling Platform**

- **Single-Page Routing & Interactive Calendar:** Real-time patient appointment management and calendar scheduling without full page reloads.
- **Role-Based Access Control:** Granular authentication separating administrative staff, dental practitioners, and patients.
- **Dedicated Data Triage:** Clean segregation of automated system notifications from direct patient inquiry messages.

<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS">
  <img src="https://img.shields.io/badge/HTML5%2FCSS3-E34F26?style=flat-square&logo=html5&logoColor=white" alt="Web">
</p>


### ⚡ Laraprof Portfolio
**High-Performance Static Portfolio with Laravel 12**

- **Blade-Driven Architecture:** Zero-database, pure Blade templating architecture delivering lightning-fast page response times.
- **Minimalist Footprint:** Modern, responsive design optimized for instant First Contentful Paint (FCP) and seamless navigation.
- **Clean Structure:** Modular components, semantic HTML5, and accessible UI hierarchy.

<p>
  <img src="https://img.shields.io/badge/Laravel_12-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Blade-F05340?style=flat-square&logo=laravel&logoColor=white" alt="Blade">
</p>

🔗 [Repository: sprout-main/laraprof](https://github.com/sprout-main/laraprof)

  </tr>
  <tr>

### 🗄️ Student Database Management System
**Desktop Academic Profiler & Records Query Engine**

- **Profile Lifecycle Operations:** Complete CRUD functionality for managing student academic profiles, enrollments, and course records.
- **SQL Query Optimization:** Structured tabular reporting with indexed querying for rapid administrative record retrieval.
- **Native GUI Interface:** Ergonomic desktop application engineered with a clean VB.NET interface.

<p>
  <img src="https://img.shields.io/badge/VB.NET-945DB7?style=flat-square&logo=dotnet&logoColor=white" alt="VB.NET">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows">
</p>

  </tr>
</table>

---

## 🛠️ Technical Arsenal

### Languages & Core Web
<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/VB.NET-945DB7?style=for-the-badge&logo=dotnet&logoColor=white" alt="VB.NET">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
</p>

### Frameworks & Web Technologies
<p>
  <img src="https://img.shields.io/badge/Laravel_11_%2F_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white" alt="Leaflet">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/Blade_Templates-F05340?style=for-the-badge&logo=laravel&logoColor=white" alt="Blade">
  <img src="https://img.shields.io/badge/RESTful_APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white" alt="REST APIs">
  <img src="https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=for-the-badge&logo=openstreetmap&logoColor=white" alt="OSM">
</p>

### Databases, Systems & Tools
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white" alt="Composer">
  <img src="https://img.shields.io/badge/UI%2FUX_Design-FF6C37?style=for-the-badge&logo=figma&logoColor=white" alt="UI/UX">
</p>

---

## 📊 GitHub Metrics

<div align="center">

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sprout-main&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="sprout-main's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sprout-main&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sprout-main&theme=tokyonight&hide_border=true" alt="sprout-main GitHub Streak" />
</p>

</div>

---

## 🎓 Education & Experience

| Period | Role | Organization | Core Responsibilities & Impact |
|:---|:---|:---|:---|
| **2023 – 2027** | **BS in Information Technology** | **Data Center Colleges of The Philippines** *(Bangued, Abra)* | Software design, and systems analysis. |
| **Internship** | **Information Technology Intern** *(288 Hours)* | **Mayor's Office, Municipality of Peñarrubia** | Provided hands-on pc configuration, digital records management, and IT support. |
| **Experience** | **Crew Member** | **McDonald's** | Developed operational agility, high-volume multitasking, teamwork under pressure, and customer service communication. |

---

## 📫 Connect & Collaborate

<div align="center">

Have a project to discuss or an engineering opportunity? Let's connect!

<p align="center">
  <a href="mailto:mandijakecarlog@gmail.com">
    <img src="https://img.shields.io/badge/Email-mandijakecarlog%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Direct">
  </a>
  <a href="https://github.com/sprout-main">
    <img src="https://img.shields.io/badge/GitHub-sprout--main-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile">
  </a>
  <a href="https://github.com/jakews2">
    <img src="https://img.shields.io/badge/GitHub-jakews2-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile">
  </a>
  <a href="https://sarak.free.nf">
    <img src="https://img.shields.io/badge/Live_Project-sarak.free.nf-10B981?style=for-the-badge&logo=googleearth&logoColor=white" alt="Sarak Live">
  </a>
</p>

<p align="center">
  🇵🇭 <strong>Philippines</strong>
</p>

<br/>

[⬆ Back to Top](#-jake-carlo-g-mandi)

---

</div>
