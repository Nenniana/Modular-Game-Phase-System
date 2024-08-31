# Modular Game Phase System

This Unity project, created as a personal passion project, seeks to offer a modular framework for managing game phases (e.g., menus, gameplay states) within a Unity game.

## Concept

The system was created with the intention of allowing developers to define and manage custom game phases and triggers in a modular way, which designers may then easily configure and combine to create larger game systems. While the foundation is provided, developers must create specific phases and triggers, after which designers can easily configure diverse phase systems.

## Features

- **Modular Phase Management**: Easily extendable framework allowing for the creation of custom game phases.
- **Realtime Inspector Feedback**: View realtime changes of both phases and triggers within the Unity Inspector.
- **Custom Trigger System**: Define custom triggers with complex conditions for more precise phase control. Triggers determine when a phase ends and can be grouped with various conditions (e.g., trigger on any, all, or a specific number met).
- **Phase Transitions**: Smooth transitions between game phases, ensuring a cohesive game experience.
- **Dependency Injection**: Utilizes dependency injection to enhance modularity and reduce coupling between components.
- **Developer-Centric**: Requires a developer to implement specific phase logic, but provides a structure that designers can leverage without deep programming knowledge.

## Potential Enhancements

- **Goto Feature**: Implement a feature allowing certain triggers to bypass the next phase and jump to a specific one instead.
- **Custom Transitions**: Adding more customizable transition effects to improve the user experience.
- **Enhanced Documentation**: Adding detailed examples and documentation.