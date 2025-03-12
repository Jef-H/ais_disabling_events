# Exploring Trends in Marine Vessel Automatic Identification System (AIS) Disabling Events

## Overview
The ocean plays a crucial role in supporting global food supplies and economic activities. The Automatic Identification System (AIS) is an essential tool for tracking vessel activity, enhancing maritime safety, and preventing ship collisions. However, disabling AIS—resulting in "AIS gaps"—raises concerns about potential illegal fishing or strategic concealment of productive fishing locations.

This project investigates AIS disabling events using a dataset from [Global Fishing Watch](https://globalfishingwatch.org/). By analyzing spatial patterns, vessel types, and the frequency of disabling events, this study aims to shed light on the motivations behind AIS gaps and their implications for marine conservation.

## Key Objectives
- Analyze patterns in AIS disabling events.
- Examine spatial distributions and vessel types involved in AIS gaps.
- Determine whether AIS gaps are linked to illegal fishing or competitive fishing strategies.
- Explore correlations with protected marine areas.

## Data Source
The dataset used in this study is publicly available from Global Fishing Watch:
[Public Welch et al. Disabling Events Dataset: v20221102](https://globalfishingwatch.org/data-download/datasets/public-welch-et-al-disabling-events:v20221102)

## Methodology
1. **Data Wrangling:**
   - Preprocessing AIS data using Python (Pandas, NumPy).
   - Cleaning and exploring dataset attributes (vessel type, flag, AIS gap duration, etc.).

2. **Statistical Analysis:**
   - Aggregating total and average AIS gap durations per vessel class.
   - Identifying regions with high concentrations of AIS gaps.

3. **Geospatial Visualization:**
   - Heatmaps of AIS disabling event locations.
   - Overlays with protected marine areas (Protected Planet dataset).
   - Analysis of AIS gaps near restricted fishing zones.

## Installation & Dependencies
To replicate the analysis, install the following dependencies:
```bash
pip install pandas numpy geopandas seaborn matplotlib geopy
```

## Results
- Identified **two major hotspots** of AIS disabling: one northeast of Japan and another between Argentina and the Falkland Islands.
- Analysis suggests AIS gaps may serve **both strategic and illicit purposes**:
  - **Strategic Concealment:** AIS is disabled to hide productive fishing locations.
  - **Illegal Activity:** Some gaps align with regions known for illicit fishing.
  - **Operational Challenges:** Equipment failure and environmental factors can also contribute.

## Future Work
- **Refining vessel classification**: Further breakdown of vessel types with AIS gaps.
- **Machine Learning Applications**: Developing predictive models for AIS gap detection.
- **Policy Recommendations**: Collaborating with conservation agencies to improve maritime oversight.

## References
- [Global Fishing Watch AIS Disabling Dataset](https://globalfishingwatch.org/data-download/datasets/public-welch-et-al-disabling-events:v20221102)
- [Protected Planet Marine Areas](https://www.protectedplanet.net/en/search-areas?filters%5Bis_type%5D%5B%5D=marine)
- [Windward: "Mind the AIS Gap"](https://windward.ai/blog/mind-the-ais-gap/)

## Contact
For questions or collaboration, feel free to reach out!

---

This README provides a professional summary of your project, making it clear and engaging for GitHub users. Let me know if you'd like any modifications!
