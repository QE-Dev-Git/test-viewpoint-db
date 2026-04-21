# Test Viewpoint Database

## Overview
This repository contains a structured database of test viewpoints derived from defect analysis.

The purpose is to improve test design quality, eliminate dependency on individual skills, and enable AI-assisted test design using Devin.

---

## Objectives

- Prevent defects before they occur (not just detect them)
- Standardize test viewpoints across projects
- Enable AI-driven test design and review
- Capture and reuse knowledge from past defects

---

## Repository Structure

- test_viewpoint_db_project.md  
  → Project-specific test viewpoint database

---

## Core Concept

All defects must be structured using the following three elements:

- Condition
- Action
- State

Test viewpoints must be generated based on combinations of these three elements.

---

## Usage (For Humans)

### 1. Test Design

- Refer to the viewpoint database
- Extract relevant viewpoints
- Expand them using:
  - Condition × Action × State
- Prioritize:
  - In-progress states
  - State transition boundaries
  - Exceptional conditions

---

### 2. Defect Analysis

- Break down defects into:
  - Condition
  - Action
  - State
- Convert them into reusable test viewpoints
- Add them to the database

---

## Usage (For Devin / AI)

- ALWAYS refer to this database when generating test cases
- Generate viewpoints using:
  - Condition × Action × State
- Do NOT rely on single viewpoints — combine multiple conditions
- Consider:
  - UI consistency
  - Data integrity
  - State consistency
- Prioritize:
  - In-progress scenarios
  - Boundary conditions
  - Exceptional cases

---

## Update Rules

- Every new defect MUST be added to this database
- Each entry must include:
  - Condition
  - Action
  - State
  - Viewpoints
- Keep viewpoints reusable and specific
- Avoid overly abstract descriptions

---

## Important

This database is NOT just for reference.

It MUST be actively applied to test design.

Test design without using this database is NOT allowed.
