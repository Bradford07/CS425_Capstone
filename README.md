# Halo Vision

**An Augmented Reality Assistance System for Visually Impaired Skiers**

## Overview

Halo Vision is a capstone project exploring the use of augmented reality (AR) to help people with visual impairments navigate outdoor trails with greater awareness and independence.

The project targets adaptive skiing, with the goal of making trail information easier to perceive through alternative visual representations and other sensory feedback. Halo Vision is designed to **supplement trained human guides, not replace them**.

The application is being developed for Microsoft HoloLens 2 using Unity. The initial prototype establishes the development environment and tests deployment to the headset. Future development will investigate live camera-based terrain visualization, image enhancement, and methods for communicating trail direction and boundaries.

## Project Goals

- Investigate the feasibility of using HoloLens 2 for adaptive outdoor navigation.
- Explore live camera-based terrain visualization for users who have difficulty seeing the surrounding environment.
- Investigate image-processing and machine-learning techniques for distinguishing traversable trail from surrounding terrain.
- Explore accessible guidance methods, including high-contrast visual displays and nonvisual feedback.
- Evaluate the technical constraints of real-time camera processing and augmented reality on HoloLens 2.

## Technology Stack

- **Unity** — application development and scene creation.
- **C#** — application scripting.
- **Microsoft HoloLens 2** — target augmented reality hardware.
- **OpenXR** — XR runtime and interaction support.
- **Visual Studio 2022** — building and deploying the application.
- **Git and GitHub** — source control and collaboration.

## Current Development Status

The project is in its initial prototyping stage.

**Implemented**
- Unity project configured for Universal Windows Platform (UWP).
- OpenXR configured for the HoloLens 2 development workflow.
- Basic Hello World scene created.
- Prototype successfully built, deployed, and launched on the HoloLens 2.
- Initial text sizing adjusted to improve visibility in the headset.

**Planned**
- Access and display the HoloLens 2 camera feed.
- Create a head-locked terrain-view panel.
- Investigate image enhancement techniques for improved visibility.
- Explore trail segmentation and traversability classification.
- Investigate spatial audio and other accessible feedback methods.
- Evaluate performance, latency, and usability.

These planned features have not yet been implemented and will be evaluated as development progresses.

## Development Environment

The current development setup uses:

- Windows 11
- Unity 2022.3
- Visual Studio 2022 Community
- Microsoft HoloLens 2
- OpenXR Plugin for Unity

Exact package versions and configuration details may change as the project develops.

## Repository Structure

```text
CS425_Capstone/
├── Assets/          # Scenes, scripts, and project assets
├── Packages/        # Unity package manifest and dependencies
├── ProjectSettings/  # Unity project configuration
├── .gitignore        # Files excluded from version control
└── README.md         # Project documentation
```

Unity-generated folders and build outputs are excluded from version control where appropriate.

## Safety and Intended Use

Halo Vision is an experimental accessibility project. It is not a certified navigation or safety system. Any future trail guidance must be evaluated carefully for reliability, latency, environmental conditions, and usability before real-world use. The project is intended to support adaptive-sports participants and trained guides, not replace established safety practices or human supervision.

## Project Team

This project is being developed as part of a university capstone. Team roles, advisors, and acknowledgments can be added here as the project progresses.

## License

No license has been specified yet. Unless a license is added, the repository should not be assumed to grant others permission to reuse or redistribute its contents.
