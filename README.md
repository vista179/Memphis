# Memphis

Memphis is the code name for a reliable operating system designed from the ground up using the Orbis environment, C, and C++. The project aims to provide a stable, user-friendly system experience with a focus on reliability and graceful recovery.

Unlike traditional systems that display a crash screen, Memphis is designed to show a simple message box asking whether the user wants to reboot the computer to fix a crash or fatal error. This keeps failures more manageable and avoids a harsh, confusing crash experience.

## Overview

Memphis is built with the goal of creating a dependable operating system that prioritizes:

- reliability
- clean recovery flow
- simplicity
- performance
- maintainability

The project is centered around a practical philosophy: when something fails, the system should guide the user through a calm, understandable recovery process instead of forcing a confusing crash experience.

## SIFS

Memphis uses **SIFS**, short for **Small Image File System**, as its system disk format.

SIFS is designed to store the same amount of files in significantly less space. For example, a 500 GB collection of files could potentially occupy only 250 GB when stored using SIFS, depending on the data and the efficiency of the format. This allows Memphis to make better use of available storage without removing files.

SIFS is intended to provide:

- efficient storage usage
- support for large collections of files
- compact system images
- a file system designed specifically for Memphis

## Design Goals

- Build a robust OS from the ground up
- Use Orbis, C, and C++ for low-level system design
- Use SIFS as the system disk format
- Minimize unexpected failures
- Provide simple, user-friendly error recovery
- Create a stable foundation for future development

## Core Philosophy

Memphis is designed to be resilient by default. Instead of leaving the user staring at a crash screen, it offers a direct recovery prompt to help the system recover with minimal disruption.

This reflects the project’s core idea: reliability should feel calm, understandable, and recoverable.

## Current Status

Memphis is currently in its early stages. The repository acts as the foundation for the operating system concept and is intended to grow as development continues.

## Getting Started

At this stage, the project is still being developed. As the system evolves, setup instructions, build steps, and architecture details will be added.

## Roadmap

Planned development includes:

- core architecture
- system services and kernel components
- SIFS development and integration
- crash handling and recovery flow
- user interface improvements
- stability testing and reliability work

## Contributing

Contributions are welcome as the project grows. If you’d like to help with Memphis:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Open a pull request with a clear explanation of the work

## Forks and Community Builds

If you fork this project, your fork becomes an unofficial flavor or distribution of Memphis. This means it can be customized, extended, or rebranded for your own use while still being based on the Memphis codebase and philosophy.

Community forks are welcome, but they are not official Memphis releases unless they are explicitly endorsed by the project maintainers. Any fork should retain the project’s core principles of reliability, graceful recovery, and user-friendly system behavior.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full details.

## Final Note

Memphis is a reliability-first operating system project designed to be practical, resilient, and user-friendly. The goal is to create a system that minimizes disruption and provides a cleaner recovery experience when things go wrong.
