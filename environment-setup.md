# Environment Setup Documentation

## System Specifications
- Device name: KHANG_LAPTOPS
- Processor: Intel(R) Core(TM) 7 150U @ 1.80 GHz
- RAM: 16.0 GB (15.7 GB usable)
- System type: 64-bit operating system, x64-based processor
- Pen & Touch: No pen or touch input available

## Software Versions
- Node.js: v23.7
- npm: v10.9.2 
- React Native: 0.81.1
- React Native CLI: 2.0.1
- Android Studio: 1.3.7
- VS Code: 1.103.2
- Java JDK: 21

## Setup Steps
1. Installed Node.js and npm.
2. Installed Android Studio, SDKs, and created an emulator.
3. Installed React Native CLI.
4. Created a test project using:
   ```bash
   npx @react-native-community/cli init

## Deviations from Lab Instructions
1. Gradle error due to non-ASCII folder name. Windows file path length limit (260 characters). Fix: Moved project to a shorter path

2. Deprecated init command. Fix: Documented updated command for future use npx @react-native-community/cli init
## Time Taken
1. Environment setup: ~3 hours

2. Project structure exploration: ~15 minutes

3. App modification & testing: ~30 minutes

4. Debugging & fixing errors: ~10 minutes

5. GitHub Posting: ~15 minutes
