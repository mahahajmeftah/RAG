# RAG Pipeline for Polytech Angers Regulations

## Introduction

This notebook demonstrates how to build a RAG (Retrieval-Augmented Generation) pipeline using Gemma, LangChain, and ChromaDB.

## Purpose

The RAG pipeline is designed to answer questions related to the regulations of Polytech Angers by combining a language model with a vector database. It retrieves relevant information from the regulations document and generates context-aware responses.

## Components

1. Introduction
2. Installation
3. Importations
4. Data Processing
   - Splitting the PDF into pages
   - Splitting the pages into chunks (Chunking)
5. Building the Vector Database
6. Model
7. Retrieval
8. Augmentation
9. Query
10. Generation

## Document Used

- File: "Reglement_etudes_Polytech_Angers_2020-2021.pdf"
- Content: This document outlines the rules, procedures, and guidelines for students at Polytech Angers for the 2020-2021 academic year.

## Model

- Model Name: Gemma 7B Instruction-Tuned (gemma-7b-it)
- Developer: Google
- Description: An open-source large language model with 7 billion parameters, tuned for instruction-based tasks.

## Vector Database

- Database: ChromaDB
- Description: An open-source embedding database used to store and manage text chunk embeddings from the regulations document.
