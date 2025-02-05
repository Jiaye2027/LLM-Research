# KG-Enhanced LLM for Academic Content Generation

## Overview
This research project explores the integration of Knowledge Graphs (KGs) with Large Language Models (LLMs) to improve the accuracy of AI-generated academic content. By grounding LLM outputs in structured knowledge representations, we aim to reduce hallucinations and enhance the reliability of generated content, particularly in educational contexts.

## Project Goals
- Develop a system that combines LLMs with Knowledge Graphs for more accurate content generation
- Reduce hallucinations in AI-generated academic content
- Create automated tools for generating accurate textbook summaries and study materials

## Technical Architecture
### Components
- **Large Language Models (LLMs)**
  - Based on Transformer architecture
  - Processes text through tokenization and embedding
  - Utilizes multi-head self-attention mechanisms
  
- **Knowledge Graphs (KGs)**
  - Stores structured information as entity-relationship triples
  - Example: (UCI, is_located_in, Irvine)
  - Built using Neo4j LLM Knowledge Graph Builder
  
- **Retrieval-Augmented Generation (RAG)**
  - Integrates KG with LLM using Langchain
  - Retrieves relevant facts before generation
  - Grounds responses in verified knowledge

## Current Progress
- Implemented initial KG construction pipeline using Neo4j
- Developed prototype integration using Langchain
- Successfully tested on liberal arts subjects
- Working on improving math subject processing

### Current Challenges
- Math formula representation in KGs
- KG quality maintenance


