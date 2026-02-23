---
layout: default
title: Artifact and Enhancements
---

[Home](index.md) | [Code Review](code-review.md) | [Artifact](artifact.md)

# Artifact and Enhancements

## Artifact Overview

**Project:** Weight-Tracking Application  
**Original Course:** CS 360 – Mobile Architecture and Programming  
**Technology Stack:** Java, Android SDK, SQLite  

This application was originally developed as a mobile weight-tracking system that allows users to create accounts, log weight entries, set goals, and store data locally using SQLite.

## Code (Before and After)

- **Original version (before enhancements):**  
  [View Original Code on GitHub](https://github.com/Zak-Shaw/Zak-Shaw.github.io/tree/main/original)

- **Enhanced version (after enhancements):**  
  [View Enhanced Code on GitHub](https://github.com/Zak-Shaw/Zak-Shaw.github.io/tree/main/enhanced)
  
---

# Enhancement 1: Software Design and Engineering

## Overview

The original application allowed users to log weight entries and set goal values. For this enhancement, I expanded the system to include a full workout-tracking feature. This required adding a new Activity, designing a consistent user interface, and integrating additional database functionality without disrupting existing features.

## What Was Added and Improved

- A dedicated workouts screen consistent with the existing weight-tracking layout  
- Logging of workouts by date, duration, and type  
- Dynamic table generation for displaying stored workout entries  
- Removal functionality for workout entries  
- Input validation and parsing logic to support flexible time entry  

This expansion required careful attention to structure and separation of concerns so that the new feature integrated cleanly with the existing application.

## Why It Matters

This enhancement demonstrates my ability to extend an existing codebase rather than build a small standalone program. The workout tracker increased the overall functionality of the application while maintaining consistency in design and usability.  

It also required thoughtful UI decisions to keep layouts readable across screen sizes and maintain internal data consistency despite flexible user input. These changes improved the overall maintainability and scalability of the application.

## Skills Demonstrated

- Extending an existing mobile application without breaking functionality  
- Designing consistent and user-friendly UI components  
- Integrating new database structures into an established system  
- Managing usability trade-offs while preserving clean internal data structure

---

# Enhancement 2: Algorithms and Data Structures

## Overview

The original application allowed users to enter and display stored data, but it did not process that data beyond basic retrieval. For this enhancement, I implemented sorting and calculation features for both the weights and workouts screens. These updates introduced logic that evaluates and transforms stored data rather than simply displaying it.

## What Was Added and Improved

- Toggle-based sorting for weight and workout entries  
- Queries that retrieve data in different ordered formats  
- Progress calculation between starting and current weight  
- Aggregation of total workout duration based on stored records  

These features required iterating through database results, organizing data intentionally, and converting stored values into meaningful summaries for the user.

## Why It Matters

This enhancement moved the application beyond static data entry and display. Instead of acting as a simple log, the system now processes and evaluates stored information to provide insight and feedback.  

Implementing sorting and aggregation within a real mobile application required careful handling of data consistency, internal representation, and user input variability. These updates demonstrate applied algorithmic thinking within a practical system rather than an isolated example.

## Skills Demonstrated

- Designing logic that processes and orders stored data  
- Applying sorting and aggregation techniques within an application context  
- Managing trade-offs between simplicity, performance, and readability  
- Integrating new logic without disrupting existing functionality  

---

# Enhancement 3: Databases


## Overview

The original application stored weight entries using a single-purpose database structure. For this enhancement, I expanded the database schema to support workout tracking alongside weight data. This required designing a new workouts table, updating the database helper, and integrating the additional data into the application workflow.

## What Was Added and Improved

- Creation of a dedicated workouts table  
- Updates to the database helper to manage new queries and CRUD operations  
- Support for user-specific workout records  
- Queries to retrieve, sort, and aggregate stored workout data  

These changes transformed the application from a single-function tracker into a more flexible system capable of managing multiple related data types.

## Why It Matters

This enhancement demonstrates practical database design within a real application environment. Expanding the schema required careful planning to ensure new tables and queries did not interfere with existing functionality or user data.  

The updated structure supports persistent storage, controlled data retrieval, and scalable feature expansion. By moving from a simple data model to a more structured and extensible design, the application became more maintainable and adaptable.

## Skills Demonstrated

- Designing and extending relational database schemas  
- Writing and integrating structured queries within an application  
- Managing user-linked records and data integrity  
- Planning database changes without disrupting existing systems  

---

# Course Outcomes Alignment

This section explains how the enhancements support the five CS 499 course outcomes.

(
