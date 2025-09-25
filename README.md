# 7-Day-AI-Agents-Email-Crash-Course

This repo is about my 7-Day AI Agent Crash Course

In this course, I will build a conversational AI agent that can answer questions about any GitHub repository. It acts as a personal assistant for code and documentation, similar to DeepWiki but tailored to my own repositories.

The process involves:

Downloading and processing data from the repository

Indexing it in a search engine

Connecting the search engine to the agent

In the first half of the course, I focus on preparing the data.


This notebook implements helper functions for an ingestion pipeline. It fetches markdown documentation files from GitHub repositories, splits and organizes them into smaller sections, and prepares them for downstream tasks such as indexing or analysis. The key steps include data retrieval (read_repo_data), segmentation (split_markdown_by_level, sliding_window), and preprocessing (intelligent_chunking). These functions work together to convert large unstructured markdown content into structured, analyzable units.
