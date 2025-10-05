# Topic 2 — Assignments

Assignment 1 — File formats: JSON & YAML
- Objective: Read/write structured config/data formats.
- Description: Build a tool that converts between JSON, YAML, and CSV for simple tabular records. Preserve field types where possible.
- Requirements: CLI with input/output format flags, error handling for malformed files.
- Deliverables: converter.py, tests, example files, README.
- Difficulty: Easy

Assignment 2 — Working with large files
- Objective: Process files efficiently (memory-conscious).
- Description: Implement a streaming processor that counts unique users per day from a newline-delimited JSON (ndjson) log file without loading all data into memory.
- Requirements: Use generators/iterators; show memory usage benchmark on a ~1GB synthetic file.
- Deliverables: processor.py, script to generate synthetic ndjson, benchmark notes.
- Difficulty: Medium

Assignment 3 — Binary formats (Parquet)
- Objective: Learn parquet usage for tabular data storage.
- Description: Convert a CSV dataset to Parquet partitioned by year/month, and demonstrate a fast predicate read (e.g., filter by month) with pyarrow or pandas.
- Requirements: show time comparison CSV vs Parquet for read+filter.
- Deliverables: conversion script, sample data, benchmark report.
- Difficulty: Medium