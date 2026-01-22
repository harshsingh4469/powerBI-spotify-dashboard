Spotify Analytics Dashboard (Power BI)
Overview

This project is an interactive Power BI dashboard built using Spotify dataset (Top 50 tracks). It provides insights into music trends, artist performance, popularity patterns, explicit content distribution, and track characteristics using advanced DAX measures and clean visuals.

The dashboard is designed as a portfolio project to demonstrate skills in Power BI reporting, DAX, KPI design, and storytelling with data.

Features / Insights Covered

Key KPIs: Total Songs, Distinct Songs, Distinct Artists

Popularity Analysis: Average / Max / Min popularity

Track Duration Insights: Average / Min / Max duration (minutes)

Explicit Content Analysis: Explicit songs count, Non-explicit songs count, Explicit %

Ranking Analysis: Avg position, #1 ranked songs and artists

Album Type Insights: Single vs Album counts, Album type distribution

Artist-level Analysis: Songs per artist, popularity per artist, #1 hits per artist

Time-based Analysis (if year exists): songs per year, popularity trend, explicit % per year

Tech Stack

Power BI Desktop

Power Query (Data Cleaning & Transformation)

DAX Measures (KPI creation, calculated metrics, category splits)

Interactive Visuals (Cards, bar charts, donut charts, slicers, tables)

Dataset

Source: Spotify Charts dataset (Top tracks)

Format: CSV

Example fields used:

song, artist

popularity

duration_ms

is_explicit

position

album_type, total_tracks

(Optional) year

Dashboard Pages (Suggested Structure)

Overview

KPI Cards: Total Songs, Artists, Avg Popularity

Popularity summary charts

Explicit Content

Explicit vs Non-explicit split (Donut + KPI)

Avg popularity comparison

Artist Insights

Songs per artist

Popularity per artist

#1 hit artists

Ranking & Album Insights

Position-based analysis

Album type distribution

Key DAX Measures

Examples of measures created:

Total Songs / Distinct Songs / Distinct Artists

Avg / Max / Min Popularity

Avg duration in minutes (conversion from ms)

Explicit Count, Non-explicit Count, Explicit %

Position 1 songs and artists

Songs per year and explicit % per year (if date/year exists)

How to Use

Download the dataset (CSV file).

Open the .pbix file in Power BI Desktop.

Update dataset path if required:

Home → Transform Data → Data Source Settings

Refresh the report:

Home → Refresh

Use slicers to filter:

Artist, album type, explicit content, year (if available)

Project Objective

To build a portfolio-ready analytical dashboard showcasing:

Strong Power BI fundamentals

DAX measure creation at scale (DAX Query View)

Data visualization best practices

Business-style insights and storytelling
