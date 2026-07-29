# indiramahadiva.github.io

Personal portfolio site for **Putu Indira Mahadiva Arysaputri** — Data Engineering student at Stockholms Tekniska Institut (STI), Stockholm.

🔗 **Live site:** [indiramahadiva.github.io](https://indiramahadiva.github.io/)

---

## About

I'm training as a Data Engineer with a focus on data platform development, pipeline design and AIOps. This site collects the projects I've built during my studies — from Python fundamentals through to end-to-end medallion-architecture pipelines on Databricks.

**Currently looking for an LIA (internship) placement, January–May 2027 (weeks 2–21), in the Stockholm area.**

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| **Marathos** | End-to-end data platform on the Kaggle Ultra-Marathon dataset (~7.5M rows, 1798–2022). Bronze → Silver → Gold star schema, scheduled daily pipeline, streaming table, AI/BI dashboard and Genie space. | PySpark · Databricks · Unity Catalog · Delta Lake · SQL · Lakeflow Declarative Pipelines |
| **IoT Sensor Pipeline** | Team-built event-driven platform streaming sensor data from a simulated fleet of 1,200 home appliances through a Bronze → Silver → Gold pipeline, surfacing predictive-maintenance insights in a live dashboard. | Medallion architecture · streaming · dashboarding |
| **Sakila DVD Rental Analysis** | End-to-end analytics pipeline: dlt migration from SQLite into DuckDB, SQL exploratory analysis and KPIs, delivered as an interactive Evidence BI dashboard with revenue, customer and category insights. | dlt · DuckDB · SQL · Evidence |
| **F1 Trackmetrics** | Cross-discipline project with UX students building an interactive analytics dashboard on Formula 1 race data from the Italian Grand Prix at Monza (2023–2025). | Python · SQL · dashboarding · agile teamwork |
| **YrkesCo Database** | Relational database design for a fictional vocational college, replacing scattered Excel tracking of students, courses, programs, instructors and consultants. Full conceptual → logical → physical modeling, normalized to 3NF with test data and join queries. | PostgreSQL · ER modeling · normalization |
| **Geometry OOP** | Python library modeling 2D/3D geometric shapes with inheritance, polymorphism and operator overloading, plus a matplotlib plotter and a full pytest suite. | Python · OOP · pytest · matplotlib |
| **DNA Sequence Analysis** | Parses DNA sequence files in two formats (single-line and multi-line), computes A/T/C/G nucleotide frequencies and visualizes results as bar charts. | Python · matplotlib |

---

## Built with

- HTML5 / CSS3 / vanilla JavaScript
- Static site, no build step
- Hosted on GitHub Pages

---

## Repository structure

```
.
├── index.html          # single-page site
├── assets/
│   ├── css/            # stylesheets
│   └── js/             # scripts
├── images/             # project thumbnails
└── README.md
```

---

## Running locally

Clone the repo and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/indiramahadiva/indiramahadiva.github.io.git
cd indiramahadiva.github.io
python -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Deployment

The site deploys automatically via GitHub Pages on every push to `main`. Because the repository is named `indiramahadiva.github.io`, it publishes to the root domain rather than a subpath.

---

## Contact

- **Email:** indiramahadiva1@gmail.com
- **LinkedIn:** [putu-indira-mahadiva-arysaputri](https://www.linkedin.com/in/putu-indira-mahadiva-arysaputri-791639199/)
- **GitHub:** [@indiramahadiva](https://github.com/indiramahadiva)
- **Location:** Stockholm, Sweden
