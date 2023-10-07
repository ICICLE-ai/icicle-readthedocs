.. ICICLE-READTHEDOCS documentation master file, created by
   sphinx-quickstart on Fri Sep 22 18:49:36 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Software and Cyberinfrastructure
==============================================

.. toctree::
  :caption: AI for CI-for-AI
  :maxdepth: 1
  :hidden:

  docs/ICICLE_Foodshed_Parser.md
  docs/PPOD_CA.md
  docs/Region2vec.md
  docs/Species-Classification-Multimodal-Context.md
  docs/Store_Closure_Website.md

Release 2023-06
#########################
Intelligent Cyberinfrastructure
###################################
AI Foundations
******************

- :ref:`ICICLE Foodshed Parser v0.1 <Constrained Language Models Yield Few-Shot Semantic Parsers>`
    - A Conversational AI model, which users can interact with it regarding food insecurity queries. The model responds with a list of commands in which an agent-based model can be run to simulate food insecurity levels in a given region.
- :ref:`Region2vec v1.0 <Region2vec>`
    - Region2vec is a Community Detection algorithm on Spatial Networks that uses graph embeddings with node attributes and spatial interactions. Region2vec first generates node embeddings for regions that share common attributes and have intense spatial interactions, and then applies clustering algorithms to detect communities based on their embedding similarity and geographic adjacency.  
- :ref:`Species Classification using Multimodal Heterogeneous Context v0.1.0 <Species Classification using Multimodal Heterogeneous Context>`
    - A species classification model that utilizes heterogeneous image contexts organized in a multimodal knowledge graph. The multimodal knowledge graph may include diverse forms of heterogeneous contexts that pertain to different modalities, such as numerical information for locations and time, categorical data for species/taxon IDs, and visual content such as images.

Use Inspired Science
###################################
Smart Foodsheds
******************

- :ref:`Persons-Projects-Organizations-Datasets_California (PPOD_CA) Knowledge Graph v23.06 <PPOD_CA>`
    - PPOD_CA is a knowledge graph of PPOD information describing connections between environmental conservation and the food system in California. 
- :ref:`Kroger Store Closure v0.1 <Store_Closure_Website>`
    - This prototype web application provides users with an engaging and interactive platform to explore an agent-based model. The model allows for dynamic simulations and captures the complex interactions between different types of households and markets. By utilizing this model, users can gain valuable insights into the food insecurity levels experienced by various types of households. For more inforamtion please visit Store_Closure_Website_.

.. _Store_Closure_Website: https://github.com/ICICLE-ai/Store_Closure_Website
