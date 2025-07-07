# Open Data Management Project - Sicilian Schools 5-Star Dataset

## Project Description

This project transforms open datasets about Sicilian educational institutions into a 5-star RDF knowledge base following Linked Open Data principles. The goal is to create a comprehensive semantic resource that encompasses all information about Sicilian schools, their environments, and quality assessments.

## Objectives

- Collect and integrate data from various sources on Sicilian school systems
- Clean and process datasets to ensure data uniformity and quality
- Transform data into RDF format following a custom OWL ontology
- Create interlinking with external resources like DBpedia
- Implement data visualizations and an interactive map
- Achieve 5-star level according to Tim Berners-Lee's model

## Datasets Used

1. **School Environment and Area (a.y. 2020-2021)**
   - Informazioni sul contesto ambientale degli edifici scolastici
   - License: IODL 2.0

2. **School Self-Assessment Results Section**
   - Valutazioni su risultati scolastici, prove nazionali, competenze
   - License: IODL 2.0

3. **Assessment Rubric Used by Schools**
   - Criteri di qualità per l'autovalutazione
   - License: IODL 2.0

4. **Schools, Students and Classes 2021-2022**
   - Dati su alunni e classi delle scuole siciliane
   - License: CC-BY-4.0

5. **Educational Institutions**
   - Anagrafica delle istituzioni scolastiche siciliane
   - License: IODL 2.0


## Interactive Map

An interactive map was created using uMap from OpenStreetMap showing:
- Geographic location of all Sicilian schools
- Additional information accessible by clicking on markers
- Visualization on cartographic base

Map link: [Sicilian Schools uMap](https://umap.openstreetmap.fr/it/map/scuole-sicilia_1084546)

## Technologies Used

- **OpenRefine**: Data cleaning and standardization
- **Python**: Processing and transformation
  - pandas: Dataset manipulation
  - rdflib: RDF triple creation
  - OSMPythonTools: Geocoding with Nominatim
  - SPARQLWrapper: SPARQL endpoint queries
  - matplotlib: Visualizations
- **Protégé**: OWL ontology design
- **uMap**: Interactive mapping


## License

The datasets used maintain their original licenses:
- IODL 2.0 (Italian Open Data License)
- CC-BY-4.0 (Creative Commons Attribution)
