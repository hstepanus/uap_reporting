GEOG 576 Mid Term Project
# 🛸 UAP Sightings Map

## Overview
**UAP Sightings Map** is an interactive, mobile-optimized web application designed for collecting and visualizing Unidentified Aerial Phenomena (UAP) sightings submitted by the public. The application leverages ArcGIS Online and Survey123 for data collection and visualization, styled with a sci-fi inspired theme to enhance user engagement.

This project was developed as part of UW GEOG 576 programming course to demonstrate skills in geospatial web development, user interaction design, and spatial data integration.

---

## Features

- 🌍 **Interactive Web Map**  
  Displays all submitted UAP sightings using custom-designed icons.

- 🧑‍💻 **Survey123 Integration**  
  Users can report sightings via a linked ArcGIS Survey123 form.

- 🖼️ **Image Attachments**  
  Each sighting can include one photo, displayed directly in the popup.

- 💡 **Custom Popups**  
  Each point includes time of incident, description, creator name, and an attached image if available.

- 🧭 **Mobile-Responsive Design**  
  Optimized for use on smartphones with clean layout and expandable legend.

- 🎨 **Thematic Design**  
  Sci-fi styling with neon buttons, Orbitron font, and a dark basemap for immersive experience.

---

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Mapping API**: [ArcGIS API for JavaScript 4.26](https://developers.arcgis.com/javascript/)
- **Data Collection**: [ArcGIS Survey123](https://survey123.arcgis.com/)
- **Data Hosting**: ArcGIS Online Feature Layer

---

## How to Use

1. **Open the Web App**  
   View and explore existing UAP sightings on the interactive map.

2. **Report a Sighting**  
   Click the “Report a Sighting” button to launch the Survey123 form and submit details (time, description, image, etc.).

3. **View Popups**  
   Click any UFO icon to view submitted information and images.

---

## Data Sources

| Dataset              | Source                                               |
|----------------------|------------------------------------------------------|
| UAP Sighting Reports | ArcGIS Survey123 Feature Layer (Hosted on AGOL)     |
| Basemap              | Esri "Streets (Night) Vector" Basemap               |
| Custom Icons         | Created via AI tools and image editing              |

---

## ER Diagram

The application's data model consists of two main tables:

- **UAP_Observation**: Contains primary attributes like description, incident time, creator, etc.
- **Attachment**: Stores image file URLs linked to each observation via object ID.

---

## Credits

- Designed and developed by **David A. Kimmel**
- Part of **GEOG 576: GIS Web Development** at the University of Wisconsin

🛸 Inspired by the unknown — built with curiosity.
