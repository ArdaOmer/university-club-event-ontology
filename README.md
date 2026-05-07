# University Club and Event Management Ontology

## Overview

This project is an ontology engineering project developed for the Knowledge Engineering and Ontologies course. The ontology models university student clubs, students, memberships, events, attendance records, announcements, recommendations, interests, event categories, locations, and semantic relationships between these concepts.

The ontology was extended during Phase 2 in order to support semantic querying, ontology-driven recommendation concepts, ontology reuse, and semantic web documentation.

---

## Domain

The selected domain is university club and event management.

---

## Purpose

The purpose of this ontology is to provide a structured and machine-understandable semantic knowledge model for representing university clubs, students, memberships, events, participation information, recommendations, interests, and semantic relationships.

The ontology is designed to support:

- Semantic querying
- Ontology-driven information retrieval
- Recommendation support
- Future intelligent campus assistant systems
- Semantic web applications

---

## Scope

The ontology focuses on:

- Student clubs
- Students
- Club memberships
- Club events
- Event attendance
- Event categories
- Event locations
- Event organizers
- Student interests
- Recommendations
- Announcements
- Semantic questions

The ontology does not model:

- Full university administration
- Academic transcript systems
- Payroll systems
- Financial management systems
- Human resources processes
- Detailed academic course management

---

## Core Concepts

### Initial Concepts

- Student
- Club
- Event
- Membership
- Attendance
- Location
- EventCategory
- Organizer

### Extended Concepts (Phase 2)

- Announcement
- Interest
- Recommendation
- SemanticQuestion
- Role

---

## Main Relationships

- A student can be a member of a club.
- A club can organize events.
- A student can attend events.
- An event can have a location.
- An event can belong to a category.
- An event can have an organizer.
- A student can have interests.
- Events can match student interests.
- Recommendations can recommend events to students.
- Events can contain announcements.

---

## Competency Questions

1. Which students are members of a specific club?
2. Which events are organized by a specific club?
3. Which students attended a specific event?
4. Which events belong to a specific category?
5. Where and when does a specific event take place?
6. Which clubs organize technology-related events?
7. Which students participated in more than one event?
8. Which events match a student’s interests?
9. Which events are recommended for a specific student?
10. Which announcements belong to a specific event?
11. Which clubs organize artificial intelligence related workshops?
12. Which semantic questions can be answered by the ontology?

---

## Ontology Expansion (Phase 2)

The ontology was extended in Phase 2 with:

- Recommendation support
- Semantic querying concepts
- Interest modeling
- Announcement structures
- Additional object and datatype properties
- Ontology reuse using schema.org and FOAF
- Widoco ontology documentation
- GitHub Pages publication

---

## Research Integration

The project integrates concepts inspired by ontology-based university question answering systems and semantic recommendation approaches discussed in the Week 11 and Week 12 research materials.

The ontology extension supports future semantic querying and ontology-driven recommendation functionality for university club and event management scenarios.

---

## Ontology Reuse

The ontology reuses several semantic web standards and vocabularies including:

- RDF
- RDFS
- OWL
- XSD
- FOAF
- schema.org

The schema.org vocabulary was partially reused for event and location modeling in order to improve semantic interoperability.

---

## Repository Structure

```text
ontology/
├── initial-ontology.ttl
└── university-club-event-ontology-v2.ttl

docs/
├── orsd-v1.docx
├── orsd-v2.docx
├── phase-2-report.docx
└── widoco/

notes/
└── design-decisions.md
```

---

## Online Ontology Documentation

Widoco ontology documentation is available at:

https://ardaomer.github.io/university-club-event-ontology/widoco/UniversityClubEventOntology/index-en.html

---

## WebVOWL Visualization

Interactive ontology visualization is available at:

https://ardaomer.github.io/university-club-event-ontology/widoco/UniversityClubEventOntology/webvowl/index.html#

---

## Current Status

The repository currently contains:

- Initial ontology version
- Extended ontology version (v2)
- ORSD Version 1
- ORSD Version 2
- Phase 2 report
- Widoco ontology documentation
- WebVOWL visualization
- GitHub Pages publication

---

## Future Work

Future improvements may include:

- SHACL validation shapes
- SPARQL competency queries
- Ontology reasoning support
- Automated ontology population
- Intelligent recommendation mechanisms
- Ontology-based chatbot integration
- Linked Open Data integration
