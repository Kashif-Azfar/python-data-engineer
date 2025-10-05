# Topic 1 — Assignments

Assignment 1 — Python fundamentals exercise
- Objective: Practice core Python syntax, control flow and functions.
- Description: Write a Python script that reads a CSV of users (id, name, signup_date), filters users signed up in the last 30 days, and prints a summary count by signup day.
- Requirements: use datetime, csv or pandas; include unit tests for the filter function.
- Deliverables: script (main.py), tests (test_main.py), sample CSV, README with run instructions.
- Difficulty: Easy

Assignment 2 — Data structures & algorithms
- Objective: Manipulate lists/dicts and implement a simple algorithm.
- Description: Implement a function that takes a list of event timestamps and returns contiguous sessions (gap > 30 minutes starts new session). Provide CLI to accept a file and output sessions.
- Requirements: O(n) solution preferred; include docstrings and type hints.
- Deliverables: module (sessions.py), CLI wrapper, tests, sample input/output.
- Difficulty: Medium

Assignment 3 — Packaging & virtualenv
- Objective: Package a small utility and publish instructions for reuse.
- Description: Turn one of your scripts into an installable package (setup.cfg/pyproject.toml), add a minimal console entry point, and create a requirements file.
- Requirements: include README with install and usage, verify installation in a venv.
- Deliverables: project package, pyproject.toml or setup.cfg, requirements.txt, README.
- Difficulty: Medium