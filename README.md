# Hybrid Intelligence Knowledge Graph

This repository contains the code, ontology files, mappings, and analysis notebooks for a Semantic Web project on **Hybrid Intelligence (HI)**. The project extends an existing Hybrid Intelligence ontology, populates it with instances from HI papers and scenarios, links it to external resources, and analyzes the resulting knowledge graph using symbolic and subsymbolic methods.

## Project Focus

The repository supports a research workflow centered on:

- **Ontology extension** for Hybrid Intelligence concepts
- **Instance creation** from HI literature and scenarios
- **Integration with external resources** such as DBpedia and Wikipedia
- **Knowledge graph querying and analysis**
- **Graph metrics and connectivity analysis**
- **Embedding-based link prediction**

The overall goal is to study how Hybrid Intelligence systems can be represented as a knowledge graph that captures agents, interactions, capabilities, trust, autonomy, control, decision roles, and scenarios.

## Repository Structure

```text
.
├── images/                  # Figures used in the report and generated visualizations
├── onto_with_inst/          # Ontology files with populated instances
├── pykeen_hi_outputs/       # Outputs from PyKEEN experiments
├── KG_measure.ipynb         # Graph metrics and connectivity analysis
├── KG_summary.ipynb         # High-level knowledge graph summary
├── Link_prediction.ipynb    # Embedding-based link prediction experiments
├── Linking.ipynb            # Linking ontology entities to external resources
├── SPARQL.ipynb             # SPARQL queries for symbolic KG analysis
├── addInstances.ipynb       # Instance creation notebook
├── addInstancedfinal.ipynb  # Finalized instance creation notebook
├── addInstancedMax.ipynb    # Additional instance population notebook
├── mapping.csv              # Mapping file for external linking
├── processData.ipynb        # Data preparation / processing
└── README.md
