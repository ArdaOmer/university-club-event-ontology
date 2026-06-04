# University Club and Event Management Ontology

## Project Objective

This project was developed for the Knowledge Engineering and Ontologies course. The goal is to model university clubs, students, events, memberships, attendance records, recommendations, and semantic question-answering concepts using Semantic Web technologies.

The ontology provides a machine-understandable representation of university club activities and supports knowledge graph construction, semantic querying, and future AI-assisted applications.

---

## Domain

University Club and Event Management

---

## Main Concepts

The ontology models the following core concepts:

- Student
- Club
- Event
- Membership
- Attendance
- Location
- EventCategory
- Organizer
- Announcement
- Interest
- Role
- Recommendation
- SemanticQuestion

---

## Ontology Design

The ontology was developed using METHONTOLOGY principles.

Existing ontologies reused:

- FOAF (Friend of a Friend)
- Schema.org

Examples:

- Student → subclass of foaf:Person
- Event → subclass of schema:Event
- Location → subclass of schema:Place

---

## Data Acquisition

Data was collected from university club management scenarios and manually modeled as RDF/Turtle instances.

Data sources include:

- University club records
- Student participation examples
- Event information
- Club announcements
- Recommendation examples

The collected data was mapped to ontology concepts and transformed into RDF triples.

---

## Knowledge Graph Construction

The knowledge graph consists of:

### Ontology Schema

```text
ontology/university-club-event-ontology-v2.ttl
```

### Instance Data

```text
data/club-event-data.ttl
```

The ontology schema and instance-level data were imported into GraphDB and combined into a knowledge graph.

---

## SPARQL Queries

Example semantic queries are provided in:

```text
queries/sparql-queries.rq
```

Example queries include:

- List all students
- List all clubs
- Find club memberships
- Find event organizers
- Find recommended events
- Find events matching interests
- Count events organized by clubs

---

## SHACL Validation

Validation rules are provided in:

```text
shacl/shacl-validation.ttl
```

The validation layer ensures:

- Students have IDs
- Clubs have names
- Events have titles and dates
- Events have categories and locations
- Recommendations reference students and events

---

## Ontology Documentation

Widoco documentation:

https://ardaomer.github.io/university-club-event-ontology/

WebVOWL visualization:

https://ardaomer.github.io/university-club-event-ontology/widoco/UniversityClubEventOntology/webvowl/index.html

---

## Repository Structure

```text
ontology/
│
├── university-club-event-ontology-v2.ttl

data/
│
├── club-event-data.ttl

queries/
│
├── sparql-queries.rq

shacl/
│
├── shacl-validation.ttl

docs/
│
├── widoco/

report/

presentation/

notes/
```

---

## Technologies Used

- OWL
- RDF
- Turtle
- GraphDB
- SPARQL
- SHACL
- Widoco
- GitHub Pages

---

## Team Members

Arda Ömer

Manisa Celal Bayar University

Knowledge Engineering and Ontologies

---

## Future Work

Possible future extensions include:

- Automatic ontology population using LLMs
- Semantic question answering
- Personalized event recommendation
- SHACL advanced constraints
- SPARQL endpoint deployment
- Real-time knowledge graph updates
