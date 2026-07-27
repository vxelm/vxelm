# Axel Guzmán

Systems Engineering student at ESCOM-IPN, focused on data engineering.

## Projects

**[rosetta-project](https://github.com/vxelm/rosetta-project)** — End-to-end streaming system for urban mobility. Python simulator emits GPS and passenger events into PostgreSQL + PostGIS; a Streamlit dashboard renders live fleet state, route deviations, and revenue. Uses event sourcing for passenger lifecycle and a demand model calibrated as a sum of Gaussians.

**[kavak-scraper](https://github.com/vxelm/kavak_scraper)** — Three-stage ETL pipeline that builds a historical dataset of used-car prices and financing terms from Kavak México. Concurrent crawler with retry and User-Agent rotation, Pydantic validation, idempotent persistence to PostgreSQL.

**[kavak-analyzer](https://kavak-analyzer.streamlit.app)** ([code](https://github.com/vxelm/kavak-analyzer)) — Interactive dashboard for used-car market segmentation. Consumes the dataset produced by kavak-scraper. K-Means clustering identifies three market tiers and a depreciation barrier at ~70,000 km. Deployed to Streamlit Cloud.

## Stack

Python · SQL · PostgreSQL / PostGIS · Docker · SQLModel · Pydantic · BeautifulSoup · Streamlit

## Background

Before Computer Science, I studied International Relations at UNAM. That program strengthened how I frame problems — starting from the business question before the technical solution — and developed my English to B2+.

## Contact

[LinkedIn](https://www.linkedin.com/in/axelm45/) · [Email](mailto:axguzvega@gmail.com)
