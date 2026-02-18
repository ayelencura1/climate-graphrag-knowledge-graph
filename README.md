# Climate Adaptation Knowledge Graph with GraphRAG

This project was developed as part of my MSc in Computational Linguistics and Large Language Models.

## Overview

This project transforms a large climate adaptation corpus into a structured Knowledge Graph and evaluates its use within a Graph Retrieval-Augmented Generation (GraphRAG) system.

The goal is to demonstrate how structured knowledge enables deeper reasoning and more contextual responses compared to traditional text-based retrieval.

## Pipeline

### 1. Corpus Construction

* 2,800+ scientific and institutional documents
* Sources include IPCC, World Bank, UNDRR, OpenAlex, arXiv and Climate-ADAPT
* Data cleaning, normalization and deduplication

### 2. Ontology Design

A domain ontology was developed to represent key concepts:

* Climate hazards
* Impacts
* Adaptation measures
* Sectors
* Vulnerable social groups
* Geographic context

Ontology design was supported by LLM-assisted concept induction and manual validation.

### 3. Knowledge Graph Construction

* Schema-guided information extraction using LLMs
* Strong ontological constraints to reduce hallucinations
* Iterative validation and refinement
* Evidence-grounded nodes and relationships

### 4. GraphRAG Experiments

The graph was integrated into a GraphRAG pipeline and compared with traditional RAG.

Results show:

* More contextual responses
* Better causal reasoning
* Improved integration of social, environmental and spatial factors

## Example Research Question

> Which vulnerable social groups are most affected by heatwaves, and what socioeconomic factors increase their exposure?

GraphRAG provided deeper and more relational explanations compared to standard retrieval.

## Technologies

* Python
* NetworkX
* Pandas
* Jupyter
* LLMs (ChatGPT, Gemini, DeepSeek, Claude)
* Prompt Engineering
* Knowledge Graphs
* GraphRAG

## Repository Structure

* `data/` – sample corpus
* `ontology/` – climate ontology (JSON)
* `graph/` – final graph sample
* `notebooks/` – pipeline demonstrations
* `prompts/` – LLM prompts
* `results/` – visualizations

## Author

Ayelén Cura
MSc Computational Linguistics & Large Language Models
Spain
