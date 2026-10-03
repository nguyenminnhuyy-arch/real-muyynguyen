# Muyynguyennn

A redesigned SwiftUI iOS workspace based on the supplied source tree.

## Build on GitHub

Push this repository to GitHub. The workflow in `.github/workflows/build-ios.yml` will:

1. Run on a macOS GitHub Actions runner.
2. Install XcodeGen.
3. Generate `Muyynguyennn.xcodeproj` from `project.yml`.
4. Build an unsigned iOS Simulator app.
5. Upload `Muyynguyennn-iOS-Simulator.zip` as a workflow artifact.

### Important

The GitHub build is intentionally **unsigned** and targets the iOS Simulator. Installing a real iPhone build requires an Apple Developer signing setup (certificate + provisioning profile).

## Project identity

- Display name: `Muyynguyennn`
- Bundle identifier: `com.muyynguyennn.app`
- Minimum iOS: 16.0
- Version: 2.0.0
