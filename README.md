[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/selinelmas/geoai-autonomous-geocaching/blob/main/geoai_geocaching.ipynb)
# geoai-autonomous-geocaching
An autonomous geospatial hunt agent in Istanbul.
GeoAI Autonomous Geocaching Agent
Project Purpose:
This project aims to transform the traditional geocaching experience into an autonomous journey by combining modern geographic information systems with generative artificial intelligence. The goal is to move beyond static routes and create an intelligent game engine that understands the spatial context and generates dynamic, data-driven clues at every stage.

Accomplishments:
I developed an end-to-end software architecture that integrates geographic data and AI. The implementation consists of four main steps:
Geospatial Data Integration: I extracted pedestrian network data for the Beyoğlu district from OpenStreetMap to build a topological model.
Spatial Analysis and Autonomous Routing: I implemented a system that calculates the shortest pedestrian routes between locations using the Dijkstra algorithm.
Setting up the LLM Agent: I designed an autonomous agent using the Google Gemini API to generate mystic riddles based on the attributes of each target location.
Interactive Visualization: I visualized all analysis results and 300-meter spatial buffer zones on interactive Folium maps.

Why I Chose This Project?
As a Geomatics Engineering student, I wanted to transform theoretical geographic analysis methods into an engaging and user-centered application. My motivation was to demonstrate how complex technical data can be converted into an immersive gamified experience.

Technical Infrastructure and Features:
OSMnx and NetworkX: Used for fetching real-world street network data and performing topological shortest-path analysis.
GeoPandas and Shapely: Utilized for coordinate system transformations from WGS84 to UTM and for calculating precise spatial buffers.
Google Gemini (AI Agent): Provided the autonomous intelligence to interpret spatial attributes and generate contextual riddles.
Folium: Enabled the visualization of analysis results through browser-based, interactive map layers.

Game Routes and Maps:
You can download the HTML files in this repository to explore the interactive maps:
- [Stage 1: Taksim Square to Galata Tower](https://selinelmas.github.io/geoai-autonomous-geocaching/GeoAI%20Project/asama1.html)
- [Stage 2: Galata Tower to Pera Museum](https://selinelmas.github.io/geoai-autonomous-geocaching/GeoAI%20Project/asama2.html)
- [Stage 3: Pera Museum to Flower Passage](https://selinelmas.github.io/geoai-autonomous-geocaching/GeoAI%20Project/asama3.html)
- [Final Stage: Flower Passage to Kilic Ali Pasha Mosque](https://selinelmas.github.io/geoai-autonomous-geocaching/GeoAI%20Project/asama4.html)
