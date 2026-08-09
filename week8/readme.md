# Week 8 - Single-Agent Smart Assistant

## Submitted By

**Mahesh Shinde**  
**Sanjivani College of Engineering, Kopargaon**  
**Student ID:** CT_CSI_DS_1141

## Overview

A Python-based Single-Agent Smart Assistant that:

- Detects user query intent
- Routes queries to appropriate tools
- Performs mathematical calculations
- Extracts keywords
- Handles general queries
- Returns structured JSON responses
- Includes error handling and logging

## Architecture

```text
User Query
    |
    v
Single Agent
    |
    +--------+---------+
    |        |         |
    v        v         v
Calculate Keywords  General
    |        |         |
    v        v         v
Calculator Keyword  Response
   Tool     Tool
    |        |         |
    +--------+---------+
             |
             v
      Structured JSON
