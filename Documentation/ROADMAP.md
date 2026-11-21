# Fleets – Development Roadmap

## Stage 0 – Environment and Repository

Objectives:
- Install Godot and configure C# development.
- Configure Git.
- Create and configure the project repository.
- Prepare `.gitignore`.
- Verify the development environment.

Current status:
- Godot 4.7.2 .NET installed.
- .NET SDK 10.0.402 detected.
- C# project successfully compiled.
- Test scene successfully launched on Windows.
- Visual Studio Code configured.
- Git repository initialized.
- Initial commit created.
- Android Studio and Android SDK postponed.

**Target result:** A verified Windows development environment and a runnable empty project.

## Stage 1 – Rules Prototype

- Coordinate representation.
- Board cells.
- Game board.
- Ships.
- Ship segments.
- Ship orientation.
- Placement validation.
- Shooting mechanics.
- Hit detection.
- Ship destruction detection.
- Game-over detection.
- Unit tests.

**Target result:** A fully working classic game rules implementation without graphics.

## Stage 2 – First Interface

- Main menu scene.
- Match configuration screen.
- Board generation.
- Ship selection.
- Ship rotation.
- Fleet placement.
- Opponent board.
- Touch-based shooting.
- Hit and miss notifications.
- Victory screen.

**Target result:** Two players can complete a local match on one device.

## Stage 3 – Artificial Intelligence

- Random ship placement.
- Basic AI.
- Hunting mode after a successful hit.
- Difficulty levels.
- Advanced strategy.
- AI behaviour tests.

**Target result:** Complete single-player gameplay.

## Stage 4 – Mobile Version

- Responsive interface.
- Different screen aspect ratios.
- Safe areas.
- Portrait and landscape orientation.
- Touch optimization.
- Haptic feedback.
- Sound effects.
- Settings menu.
- Preference persistence.
- Pause and application lifecycle handling.

**Target result:** Playable Android Alpha.

## Stage 5 – Graphics and Animations

- Final board graphics.
- Ship graphics.
- Animated water.
- Projectiles.
- Explosions.
- Smoke.
- Ship sinking animations.
- Interface animations.
- Music and sound effects.
- Skin system.

**Target result:** The game begins to reach commercial visual quality.

## Stage 6 – Local Multiplayer

- Hot-seat mode.
- Optional local Wi-Fi multiplayer.
- Session discovery.
- Room creation and joining.
- Turn synchronization.
- Connection loss handling.

## Stage 7 – Online Multiplayer

- Client-server architecture.
- Lobby.
- Matchmaking.
- Private rooms.
- Invitation codes.
- Player authentication.
- State synchronization.
- Match reconnection.
- Anti-cheat protection.
- Server-side match resolution.

## Stage 8 – Extended Game Modes

- Three and four player games.
- Larger boards.
- Teams.
- Additional fleets.
- Different victory conditions.
- Special cells.
- Obstacles.
- Fog of war.

## Stage 9 – Buffs, Debuffs and Abilities

Example effects:

- Sonar.
- Shield.
- Repair.
- Area bombardment.
- Sea mine.
- Radar disruption.
- False signal.
- Extra move.
- Fire.
- Flooding.
- Temporary immobilization.

The system must be data-driven to allow new effects without redesigning the entire game.

## Stage 10 – Commercial Preparation

- Product naming and branding.
- Visual identity.
- Privacy screens.
- Terms and agreements.
- Privacy policy.
- Analytics.
- Error handling.
- Crash reporting.
- Multi-device testing.
- Google Play closed testing.
- Application signing.
- Android App Bundle.
- Store listing.
- Production release.

## Roadmap Principles

- Stages are executed in the specified order.
- Each stage must have defined acceptance criteria.
- New functionality must not compromise existing systems.
- Architectural decisions must be documented.
- Changes to the roadmap require explicit approval.

Detailed implementation tasks are maintained in `TODO.md`.