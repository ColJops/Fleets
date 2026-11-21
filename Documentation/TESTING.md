# Fleets – Testing Strategy

## 1. Testing Objectives

Testing must ensure that Fleets remains correct, stable and maintainable throughout development.

Testing is performed at multiple levels.

## 2. Unit Testing

Unit tests will primarily cover gameplay rules and independent logic.

Planned test areas:

- Coordinate representation.
- Board cell behaviour.
- Board validation.
- Ship placement.
- Ship orientation.
- Shooting mechanics.
- Hit detection.
- Ship destruction.
- Victory detection.

## 3. Integration Testing

Integration tests will verify cooperation between game systems.

Planned areas:

- Match management.
- Player turns.
- Board interactions.
- AI integration.
- Multiplayer synchronization.
- Localization integration.

## 4. User Interface Testing

UI testing will cover:

- Menu navigation.
- Match configuration.
- Fleet placement.
- Ship selection.
- Ship rotation.
- Shooting interactions.
- Hit and miss feedback.
- Victory screens.

## 5. AI Testing

AI tests will verify:

- Valid fleet placement.
- Correct hunting behaviour.
- Difficulty differences.
- Consistent game rules.
- Expected decision behaviour.

## 6. Mobile Testing

Mobile testing will include:

- Different screen proportions.
- Portrait and landscape layouts.
- Safe areas.
- Touch input.
- Haptic feedback.
- Application pause and resume.
- Performance.

Android testing tools will be configured when required.

## 7. Localization Testing

Localization testing is mandatory.

Tests must cover:

- English language resources.
- Polish language resources.
- Missing translation detection.
- Correct language selection.
- UI text overflow.
- Different text lengths.
- Language switching.
- Adding further languages.

Gameplay logic must remain independent of localization.

## 8. Multiplayer Testing

Local and online multiplayer testing will cover:

- Turn synchronization.
- Match state consistency.
- Connection loss.
- Reconnection.
- Invalid actions.
- Match completion.

## 9. Regression Testing

Existing functionality must be retested after changes that may affect it.

Gameplay rules must remain consistent across supported game modes.

## 10. Current Environment Verification

Verified:

- Godot 4.7.2 .NET starts successfully.
- .NET SDK 10.0.402 is detected.
- C# project compilation succeeds.
- Test scene runs on Windows.
- Visual Studio Code integration works.
- IntelliSense recognizes Godot C# types.
- `dotnet build` succeeds.

Android export has not yet been verified.

## 11. Test Reporting

Testing results must record:

- Test identifier.
- Tested functionality.
- Preconditions.
- Test procedure.
- Expected result.
- Actual result.
- Pass/fail status.
- Relevant issues.

Detailed test cases will be added as systems are implemented.