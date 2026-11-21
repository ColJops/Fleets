# Fleets – Software Architecture

## 1. Architectural Goals

Fleets must be designed as a modular and extensible application.

The architecture must support:

- Classic Battleships gameplay.
- Single-player gameplay.
- Local multiplayer.
- Online multiplayer.
- Multiple board sizes.
- Additional ship types and fleets.
- Special gameplay mechanics.
- Localization.
- Future commercial development.

The initial architecture must not introduce unnecessary complexity.

## 2. Technology

- Godot 4.x .NET.
- C#.
- Visual Studio Code.
- Git.
- 2D rendering.

## 3. Architectural Principles

### Separation of Responsibilities

Gameplay rules must be separated from visual presentation.

Board representation, ship placement, shooting and victory detection should not depend on graphical nodes.

### Modular Design

Systems should have clearly defined responsibilities and interfaces.

### Testability

Gameplay rules should be testable independently of the user interface.

### Extensibility

The architecture must allow additional game modes and mechanics without requiring a complete redesign.

### Data-Driven Systems

Where appropriate, configurable game rules and gameplay effects should be represented through data rather than hardcoded behaviour.

## 4. Localization Architecture

Localization is a core architectural requirement.

Initial languages:

- English (`en`).
- Polish (`pl`).

Additional languages must be supported in the future.

Requirements:

- All player-facing text must use localization keys.
- UI text must not be hardcoded directly into gameplay code.
- Gameplay logic must not depend on the selected language.
- Translation resources must be maintained separately from gameplay logic.
- Missing translations must be detectable.
- Adding a language must not require changes to game rules.
- Language selection and persistence will be implemented in the appropriate development stage.

Polish may be used as the initial authoring language for some in-game text, but all such text must be prepared for localization.

## 5. Coding Language and Comments

C# is the primary programming language.

All source-code comments must be written in English.

Technical identifiers, class names, method names and namespaces must follow consistent English naming conventions.

## 6. Planned Architectural Areas

The following areas are expected to emerge during development:

- Core gameplay rules.
- Board and ship representation.
- Match management.
- Player management.
- AI.
- User interface.
- Localization.
- Audio and visual presentation.
- Local multiplayer.
- Online multiplayer.
- Persistence and settings.

Exact module boundaries, dependencies and interfaces remain subject to architectural design and approval.

## 7. Online Architecture

Online multiplayer is planned for Stage 7.

The client-server model is part of the project roadmap.

Server technology, hosting, protocols, persistence and authentication implementation remain TBD.

## 8. Architecture Evolution

Architecture changes must be documented in `DECISIONS.md`.

The architecture must evolve with project requirements without compromising the existing gameplay foundation.