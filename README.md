# GIS Jargon for Developers

A collaborative glossary that explains **terms with different meanings in Computer Science and GIS**.  
If you’ve ever wondered why *buffer*, *vector*, *schema*, or *routing* mean one thing in programming and something else in GIS, this repo is for you.

## Why this repo?
GIS documentation often uses words familiar to developers but with completely different meanings.  
On top of that, different organizations and standards use different names for the *same* thing — for example:  
- **LineString** in GeoJSON = **Polyline** in Esri
- **Icon** in Leaflet = **PictureMarkerSymbol** in ArcGIS

This glossary helps bridge both kinds of gaps:
- 🚧 **CS vs GIS**: different meaning for the same word  
- 🔀 **Cross-ecosystem**: different words for the same concept  

## Quick examples

| Term    | Computer Science                                  | GIS                                                           |
|---------|---------------------------------------------------|---------------------------------------------------------------|
| Buffer  | Memory area used for I/O                          | Polygon/zone created around a feature                         |
| Vector  | Array or vector                | Geometry made of points, lines, and polygons                  |
| Schema  | Database structure (tables, fields, constraints)  | Tiling schema  |
| Routing | IP packet path selection or mechanism that maps URL paths to specific views or components in a single-page application                          | Finding directions along a road/utility network               |

---

## Contributing

This project grows with community input 💡  

### 🆕 Missing a term?
Open an issue with the **Missing Term** template:
- Add the term  
- Share the meanings (CS + GIS) if you know them  
- Optionally include examples or references  

👉 [Open a missing term issue](../../issues/new?template=%F0%9F%86%95-request-a-new-term.md)

### ✍️ Improve an existing definition
If a definition is incomplete, unclear, or inaccurate, you can go to the issue and comment there.

### 💬 Start a discussion
Not sure about a definition? Think it could be explained differently?  
Open a **Discussion/Clarification** issue to get more perspectives.

👉 [Propose an improvement](../../issues/new?template=%F0%9F%92%AC-discussion---clarification.md)

---

## Other Dictionaries & References

This glossary is not meant to replace existing resources, but to complement them with a developer-focused perspective.  
If you want to dive deeper, check out these excellent references:

- [Esri developer glossary](https://developers.arcgis.com/documentation/glossary/)
- [Esri GIS Dictionary](https://support.esri.com/en/other-resources/gis-dictionary)  
- [GISGeography – GIS Dictionary / Definition Glossary](https://gisgeography.com/gis-dictionary-definition-glossary/)    
- [Lexicon of Geospatial Terminology (FGDC)](https://www.fgdc.gov/policyandplanning/a-16/lexicon-of-geospatial-terminology)
