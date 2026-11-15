# Consumer Intelligence & Demand Prediction Platform

An evidence-led portfolio project using the dunnhumby **The Complete Journey** retail dataset to study household behavior, product affinity, promotions, and sales forecasting.

## Current phase

**Phase 1 — data foundations.** The next milestone is to obtain the official dataset, inspect its files and keys, and define a precise first analysis question. Modeling and dashboard work follow the data audit.

## Data

- Primary source: [dunnhumby Source Files — The Complete Journey](https://www.dunnhumby.com/source-files/).
- Download the official release into `data/raw/`. Record the download date and file names in `reports/data_inventory.md`.
- Raw and processed data are excluded from Git. Check the source terms before sharing any derived data.
- Demographic records cover only a subset of households. The dataset has no customer reviews or inventory data.

## Project questions

1. How do household purchasing patterns differ, and which patterns are stable enough to inform decisions?
2. Which products or categories tend to be purchased together, and can held-out purchases evaluate useful recommendations?
3. How accurately can we forecast future observed sales at a clearly defined product or category and time grain?
4. How are observed discounts and campaigns associated with purchases? Causal claims require a separate research design.

## Initial structure

- `data/raw/`: downloaded source files (ignored by Git)
- `data/processed/`: reproducible outputs (ignored by Git)
- `notebooks/`: exploratory analysis and learning exercises
- `src/`: reusable code after exploratory logic stabilizes
- `reports/`: data inventory, findings, and model decisions

## Roadmap

1. Data access, schema inspection, data quality, and target definitions
2. EDA and household behavior analysis
3. Segmentation and product affinity with meaningful evaluation
4. Forecast baselines, chronological validation, and model comparison
5. Promotion analysis and anomaly investigation
6. Dashboard, documentation, and interview preparation

An independent sentiment module can be considered later with a review dataset. Its findings should be presented separately from this retailer's purchase data.

## Next task

After downloading the dataset, list each file, its size, row count, and columns in `reports/data_inventory.md`. Identify the primary and foreign keys you expect to use and flag any missing or ambiguous fields. We will review that inventory together before implementation.

