# Fleets – Release Process

## 1. Purpose

This document defines the process for preparing, verifying and releasing Fleets builds.

The release process will evolve as the project approaches commercial distribution.

## 2. Development Builds

Development builds are used to verify current functionality.

Requirements:

- Successful compilation.
- No known critical startup errors.
- Relevant tests executed.
- Changes recorded in Git.

## 3. Version Control

Git is used to maintain project history.

Development changes must be committed with meaningful messages.

Release versions must be traceable to specific commits.

## 4. Versioning

A consistent versioning scheme must be established before the first public release.

Exact versioning rules remain TBD.

## 5. Pre-Release Verification

Before a release:

- Verify successful compilation.
- Execute relevant unit tests.
- Execute integration tests.
- Verify gameplay functionality.
- Verify localization resources.
- Check supported screen layouts.
- Review known issues.
- Verify application configuration.

## 6. Android Builds

Android export configuration will be prepared when required.

The Android release pipeline must define:

- Godot export templates.
- Android SDK.
- Required build tools.
- Application identifier.
- Application signing.
- Android App Bundle generation.

Android Studio and SDK installation are currently postponed.

## 7. Testing and Distribution

The roadmap includes:

- Device testing.
- Closed Google Play testing.
- Production preparation.
- Store listing.
- Production release.

Detailed distribution procedures will be defined before the relevant stage.

## 8. Commercial Release

Commercial preparation must address:

- Privacy policy.
- Terms and agreements.
- User consent.
- Analytics.
- Crash reporting.
- Store requirements.
- Application signing.
- Release documentation.

## 9. Release Records

Each release must record:

- Version number.
- Release date.
- Included changes.
- Known issues.
- Build information.
- Relevant Git commit.
- Distribution status.

## 10. Process Changes

Changes to the release process must be documented and approved before becoming part of the official workflow.