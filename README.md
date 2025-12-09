# Cartographer Android Build

This repository builds Google Cartographer for Android using GitHub Actions.

## How to use:

1. Push this repository to GitHub
2. Go to Actions tab
3. Click "Build Cartographer for Android"
4. Click "Run workflow"
5. Wait for build to complete
6. Download the artifact `cartographer-android-build.tar.gz`

## Build Configuration:

- **Target**: Android ARM64 (arm64-v8a)
- **Min SDK**: Android 21 (Lollipop)
- **Build Type**: Release
- **Dependencies**: Abseil, Protobuf, Eigen, Ceres Solver

## Output:

The build artifact contains the compiled Cartographer library ready for use with Android NDK.
