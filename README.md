# A Continent on the Edge
### A timeline of climate disasters across Africa, 1980–2025



![Chart Preview](assets/chart_preview.png)



---

## The Story

Before working on this project, I assumed Africa was largely 
protected from the worst of climate change — after all, the 
continent contributes less than 4% of global CO₂ emissions 
and is far less industrialised than the regions driving the 
climate crisis.

I was wrong.

This project changed how I see my own continent. Tracking 
1,883 climate disaster events across Africa over 45 years, 
the data tells an uncomfortable truth: floods, droughts, 
storms, wildfires, and extreme temperatures have escalated 
dramatically — and the people least responsible for climate 
change are bearing the heaviest cost.

This visualization was built for the Storytelling with Data 
(SWD) April 2026 Challenge: *Visualize a Timeline*. But more 
than a challenge entry, it is a call to awareness — especially 
for Africans. What we understand, we can fight.

---

## Key Findings

- **1,883 climate disaster events** recorded across Africa 
  from 1980–2025
- A clear inflection point around **1999–2000**, after which 
  disaster frequency nearly doubled
- **Floods dominate** — the single largest disaster category 
  across the entire period
- A dramatic spike between **1995–2010** represents the 
  most concentrated period of climate disasters in modern 
  African history
- The last decade (2015–2025) shows sustained high frequency 
  with no signs of slowing

---

## Landmark Events Annotated

| Year | Event |
|------|-------|
| 1983 | Ethiopia & Sudan droughts — 450,000 deaths |
| 2000 | Mozambique floods — 800,000 displaced |
| 2010 | Somalia drought — 20,000 deaths |
| 2019 | Cyclone Idai — Mozambique & Zimbabwe |
| 2023 | Libya Storm Daniel — 13,200 deaths |

---

## Data Source

**EM-DAT** — The International Disaster Database  
CRED/UCLouvain, Brussels, Belgium  
[www.emdat.be](https://www.emdat.be)  
Accessed: April 2026

Filters applied: Natural disasters, Africa, 1980–2025,  
Climate-related types only (Flood, Storm, Drought, 
Wildfire, Extreme temperature)

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Python (pandas) | Data cleaning & aggregation |
| Google Colab | Analysis environment |
| Flourish | Interactive visualization |
| GitHub | Version control & portfolio |

---

## Methodology

1. Downloaded raw disaster data from EM-DAT (3,017 records)
2. Selected 5 relevant columns from 47 available
3. Filtered to climate-related disaster types only (1,883 records)
4. Aggregated individual events by year and disaster type
5. Pivoted from long to wide format for Flourish compatibility
6. Applied meaningful colour encoding by disaster category
7. Annotated 5 landmark historical events

---

## How to Reproduce

1. Clone this repository
2. Open `notebook/africa_climate_timeline.ipynb` in Google Colab
3. Upload your own EM-DAT export with the same filters
4. Run all cells in order
5. Upload `africa_climate_wide.csv` to Flourish

---

## About the Author

I am a Physics graduate (FUTO, 2025) building expertise in 
geospatial data science and AI/ML. This project sits at the 
intersection of my GIS background and a growing conviction 
that African voices and African data need to be better 
represented in global conversations about climate.

📍 Lagos, Nigeria  
🔗 [GitHub Portfolio](https://code-blize.github.io/geosim-futo)

---

*Built for the SWD April 2026 Challenge | Data: EM-DAT | 
Viz: Flourish*
