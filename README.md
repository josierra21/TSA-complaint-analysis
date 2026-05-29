# TSA Complaint Analysis: Examining Complaint Trends Across U.S. Airports

## Overview

This project analyzes Transportation Security Administration (TSA) complaint data to identify trends in passenger dissatisfaction across U.S. airports. The objective is to understand how complaint patterns have evolved over time, determine which airports generate the highest complaint volumes, and identify the categories that contribute most significantly to traveler concerns.

By combining TSA complaint records with airport location data, this analysis provides a comprehensive view of passenger experiences across the national airport system and offers data-driven recommendations for improving security screening operations.

---

## Project Objectives

This analysis seeks to answer the following questions:

- How have TSA complaints changed over time?
- Which airports generate the highest number of complaints?
- Which complaint categories occur most frequently?
- What trends exist within the Expedited Passenger Screening Program (EPSP)?
- How do complaint patterns vary across airports and geographic locations?

---

## Dataset Sources

The analysis was conducted using four datasets included in this repository:

- **complaints-by-airport.csv** – TSA complaint counts aggregated by airport and reporting period.
- **complaints-by-category.csv** – TSA complaint counts grouped by complaint category.
- **complaints-by-subcategory.csv** – TSA complaint counts grouped by complaint subcategory.
- **iata-icao.csv** – Airport reference data containing airport names, IATA codes, and geographic coordinates used for airport identification and mapping.

These datasets were combined to analyze complaint trends, identify high-volume airports, examine complaint categories, and visualize geographic patterns across the United States.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## Data Preparation

The analysis combines multiple TSA complaint datasets, including:

- Complaints by airport
- Complaints by category
- Complaints by subcategory

Airport location data was merged using IATA airport codes to provide:

- Airport names
- Geographic coordinates
- Regional information

Data cleaning and transformation were performed to standardize airport identifiers, organize complaint categories, and prepare the data for visualization and analysis.

---

## Analysis and Visualizations

### 1. TSA Complaints Over Time

A time-series analysis was conducted to evaluate national complaint trends from 2015 through 2024.

#### Key Findings

- Complaint volume increased steadily prior to 2020.
- Complaints declined sharply during the COVID-19 pandemic due to reduced travel activity.
- Complaints rose rapidly during the post-pandemic recovery period.
- Elevated complaint levels have persisted since 2022, suggesting ongoing operational challenges at many airports.

---

### 2. Airports with the Highest Complaint Volumes

A bar chart was used to identify airports generating the largest number of TSA complaints.

#### Key Findings

Several major transportation hubs consistently appear among the highest complaint-producing airports, including:

- Los Angeles International Airport (LAX)
- John F. Kennedy International Airport (JFK)
- Newark Liberty International Airport (EWR)
- Hartsfield-Jackson Atlanta International Airport (ATL)
- Denver International Airport (DEN)

These airports process substantial passenger volumes and account for a disproportionate share of national complaint totals.

---

### 3. Most Common Complaint Categories

Complaint categories were aggregated to determine which issues occur most frequently.

#### Key Findings

The **Expedited Passenger Screening Program (EPSP)** generated significantly more complaints than any other category.

Additional complaint categories included:

- Mishandling of Passenger Property
- Customer Service
- Screening Procedures
- Property Special Handling

EPSP complaints represented the largest contributor to overall complaint volume.

---

### 4. Expedited Passenger Screening Program Trends

A detailed examination of EPSP complaint subcategories was performed to identify recurring themes.

#### Key Findings

- TSA PreCheck-related complaints remained consistently prominent.
- Complaint activity increased significantly during the post-pandemic travel recovery period.
- A large number of complaints were classified as "Other," limiting visibility into specific causes of dissatisfaction.
- Complaint patterns suggest opportunities to improve consistency, communication, and traveler expectations.

---

### 5. Airport and Category Heatmap

A heatmap was created to compare complaint volumes across major airports and complaint categories.

#### Key Findings

- Complaint patterns vary considerably between airports.
- EPSP complaints appear prominently across many high-volume airports.
- Certain airports experience concentrated issues within specific complaint categories.

This visualization helps identify where targeted operational improvements may be most beneficial.

---

### 6. Distribution of Complaint Counts Across Airports

A boxplot was used to examine variability in complaint counts across categories.

#### Key Findings

- Most complaint categories exhibit relatively low variation.
- EPSP displays substantially greater variability than other categories.
- The results suggest differences in screening program implementation and passenger experience across airports.

---

### 7. Geographic Distribution of EPSP Complaints

A geographic visualization was created to examine the distribution of expedited screening complaints throughout the United States.

#### Key Findings

Major complaint concentrations were observed at:

- Los Angeles (LAX)
- New York (JFK)
- Atlanta (ATL)
- Denver (DEN)
- Miami (MIA)

The analysis indicates that complaint concentrations are associated more strongly with passenger volume and airport activity than with geographic region.

---

## Key Findings

### Expedited Passenger Screening Program Drives Complaint Volume

EPSP generated more complaints than any other TSA category and emerged as the primary contributor to nationwide complaint totals.

### Major Airport Hubs Account for a Large Share of Complaints

A relatively small number of high-traffic airports generate a substantial portion of all TSA complaints, suggesting that targeted improvements at these locations could have a meaningful national impact.

### Complaint Categorization Can Be Improved

The large number of complaints classified as "Other" limits the ability to identify specific operational issues and opportunities for improvement.

### Operational Consistency Remains Important

Variability in complaint levels across airports suggests that more standardized screening procedures and communication practices may improve the passenger experience.

---

## Recommendations

Based on the findings, the following recommendations are proposed:

1. Improve consistency in the implementation of expedited screening programs.
2. Enhance communication regarding TSA PreCheck eligibility, availability, and screening expectations.
3. Standardize operational procedures across major airport hubs.
4. Improve complaint categorization practices to support more detailed analysis.
5. Prioritize improvement initiatives at airports generating the highest complaint volumes.

---
