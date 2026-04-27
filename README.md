# University Club and Event Management Ontology

## Overview

This project is an initial ontology development project for the Knowledge Engineering and Ontologies course. The ontology models university student clubs, students, events, membership relations, attendance records, event categories, and locations.

## Domain

The selected domain is university club and event management.

## Purpose

The purpose of this ontology is to provide a structured and machine-understandable knowledge model for representing university clubs, their members, events, and participation information.

## Scope

The ontology focuses on:

- Student clubs
- Students
- Club membership
- Club events
- Event attendance
- Event categories
- Event locations
- Event organizers

The ontology does not model:

- Full university administration
- Academic transcripts
- Payroll systems
- Payment systems
- Human resources processes

## Core Concepts

- Student
- Club
- Event
- Membership
- Attendance
- Location
- EventCategory
- Organizer

## Main Relationships

- A student can be a member of a club.
- A club can organize events.
- A student can attend events.
- An event can have a location.
- An event can belong to a category.
- An event can have an organizer.

## Competency Questions

1. Which students are members of a specific club?
2. Which events are organized by a specific club?
3. Which students attended a specific event?
4. Which events belong to a specific category?
5. Where and when does a specific event take place?
6. Which clubs organize technology-related events?
7. Which students participated in more than one event?

## Repository Structure

ontology/
  initial-ontology.ttl

docs/
  orsd-draft.docx

notes/
  design-decisions.md

## Current Status

This repository contains the initial version of the ontology and a draft ontology requirements specification document.

## Future Work

Future improvements may include:

- More detailed class hierarchy
- Additional object and data properties
- SHACL validation shapes
- SPARQL competency queries
- Ontology documentation with Widoco
- GitHub Pages publication
