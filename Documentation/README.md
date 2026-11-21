# Fleets

**Fleets** is a mobile naval strategy game inspired by the classic Battleships game.

The project is developed step by step, starting with the classic gameplay experience and gradually expanding into AI opponents, local multiplayer, online multiplayer, additional game modes and advanced gameplay systems.

## Project Goals

- Build a maintainable and modular game architecture.
- Start with classic Battleships gameplay.
- Support single-player and local multiplayer.
- Introduce online multiplayer in a later development stage.
- Support additional game modes and gameplay mechanics.
- Build a commercial-quality mobile game.
- Support multiple languages from the beginning.

## Technology Stack

| Component | Technology |
|---|---|
| Game engine | Godot 4.x .NET |
| Programming language | C# |
| IDE | Visual Studio Code |
| Initial platform | Android |
| Version control | Git |
| Graphics | 2D |

## Supported Languages

Initial language support:

- English (`en`)
- Polish (`pl`)

The localization architecture must allow additional languages without requiring changes to gameplay logic.

All source-code comments and technical documentation must be written in English.

## Repository Structure

```text
Fleets/
├── Documentation/
│   ├── README.md
│   ├── ROADMAP.md
│   ├── CHANGELOG.md
│   ├── TODO.md
│   ├── ARCHITECTURE.md
│   ├── GAME_DESIGN_DOCUMENT.md
│   ├── DECISIONS.md
│   ├── TESTING.md
│   └── RELEASE_PROCESS.md
├── project.godot
├── Fleets.csproj
├── Fleets.sln
└── FleetsBootstrap.cs
```

The repository structure will evolve as development progresses.

## Development Principles

- Modular architecture.
- Separation of gameplay logic and presentation.
- Testable gameplay systems.
- Data-driven extensibility where appropriate.
- Localization-ready implementation.
- Documented architectural decisions.
- Version-controlled development.

## Current Development Status

Godot and C# development environment has been configured and verified on Windows.

Android development tools and APK export configuration are postponed until required by the project.

See [ROADMAP.md](ROADMAP.md) for the development plan.

## Documentation

All project documentation is maintained in the `Documentation/` directory.

## Project Status

Early development – Stage 0.

No production gameplay systems have been implemented yet.