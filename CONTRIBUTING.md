# Contributing to UR10e Mixed Reality

Thanks for your interest in this project. It's an early-stage prototype, so contributions of any size are welcome, from fixing a typo to adding a new interaction feature.

## Before You Start

This is a Unity project targeting Meta Quest 3. To work on it locally you'll need:

- Unity 6 (or later) with Android Build Support installed
- A Meta Quest 3 in Developer Mode (only required if you want to test on-device; the Unity Editor alone is enough for most contributions)
- Git

## Getting Set Up

1. Fork the repository
2. Clone your fork:
   ```
   git clone https://github.com/YOUR_USERNAME/ur10e-mixed-reality.git
   ```
3. Open the project folder in Unity Hub
4. Let Unity import all packages (this can take a few minutes on first open)

## How to Contribute

1. Check the [open issues](../../issues) for something to work on, or open a new issue describing what you'd like to change before starting significant work
2. Create a branch for your change:
   ```
   git checkout -b feature/short-description
   ```
3. Make your changes and test them in the Unity Editor (and on-device if possible)
4. Commit with a clear message describing what changed and why
5. Push your branch and open a pull request against `main`

## What's Useful Right Now

The project roadmap (see README) includes:

- Interactive joint manipulation by hand
- Step-by-step maintenance scenario design
- Automatic placement on a real table/surface using Scene API
- Evaluation and feedback system

Contributions in these areas are especially welcome, but improvements to existing functionality, documentation, or code organization are just as valuable.

## Reporting Issues

If you find a bug or have a suggestion, please open an issue with:

- A clear description of the problem or idea
- Steps to reproduce (for bugs)
- Your Unity version and target device, if relevant

## Code Style

- Keep C# scripts consistent with Unity's standard naming conventions (PascalCase for public members, camelCase for private fields)
- Comment non-obvious logic, especially around Articulation Body and joint control code
- Keep commits focused: one logical change per commit where possible

## Questions

Feel free to open an issue for anything that doesn't fit the above, including questions about the project's direction or how a specific piece works.
