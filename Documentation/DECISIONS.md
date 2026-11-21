# Fleets – Architecture and Project Decisions

This document records approved project decisions.

Proposals and unresolved questions must not be treated as approved decisions.

## D-001 – Game Name

**Status:** Accepted

The official game name is Fleets.

Step by Step refers to the development process, not the game's name.

## D-002 – Game Engine

**Status:** Accepted

Godot 4.x .NET is the selected game engine.

## D-003 – Programming Language

**Status:** Accepted

C# is the primary programming language.

## D-004 – Development Environment

**Status:** Accepted

Visual Studio Code is the selected code editor.

## D-005 – Graphics Technology

**Status:** Accepted

The game will use 2D graphics.

## D-006 – Initial Platform

**Status:** Accepted

Android is the initial target platform.

## D-007 – Localization From the Beginning

**Status:** Accepted

Fleets must support localization from the beginning of development.

Initial languages:

- English (`en`).
- Polish (`pl`).

The architecture must allow additional languages.

All player-facing text must use localization resources or keys.

Polish may be used for initial in-game text authoring, but localization must not be bypassed.

## D-008 – Source-Code Comments

**Status:** Accepted

All source-code comments must be written in English.

Technical identifiers and naming conventions must use English.

## D-009 – Technical Documentation

**Status:** Accepted

Project documentation is maintained in English.

The required documentation structure consists of nine files in `Documentation/`.

## D-010 – Android Development Tools

**Status:** Postponed

Android Studio and Android SDK installation are postponed until Android development and device testing become necessary.

This does not change Android's status as the initial target platform.

## D-011 – Development Order

**Status:** Accepted

Development follows the approved roadmap, Stages 0–10.

Each stage must be completed and verified before proceeding.

## D-012 – Gameplay Architecture

**Status:** Accepted

The game must use a modular and extensible architecture.

Gameplay logic must be separated from visual presentation.

## D-013 – Online Multiplayer

**Status:** Planned

Online multiplayer will use a client-server architecture.

Specific implementation decisions remain TBD.

## Open Decisions

The following topics require future approval:

- Detailed gameplay parameters.
- Board dimensions and fleet configurations.
- AI balancing.
- Online server technology.
- Authentication and persistence.
- Monetization model.
- Analytics and privacy implementation.
- Release and update strategy.

New decisions must be assigned unique identifiers and documented with their status.