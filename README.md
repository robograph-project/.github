# Robograph Project

A collection of repositories with the goal of providing a declarative specification framework for robotics sotfware projects.

Aimed primarily at ROS 2 usage. Primarily with a single-computer application as the target.

Things in mind for this project:
- Node configuration: Parameters
- Node interface: Topics (& Services & Actions)
- Graph specification: Nodes & Namespaces
- Graph configuration: All node parameters bubbled up into one definition

## Node Configuration: Parameters

- Current state of the art is https://github.com/PickNikRobotics/generate_parameter_library
- Adoption/Usage: Medium, definitely being used in the wild

## Node Interface: Topics

- Current state of the art: https://github.com/ubuntu-robotics/nodl
- Adoption/Usage: Low/None

## Graph Specification & Configuration

Currently the ROS 2 launch system is the way that this is handled.

While the launchfiles are theoretically "somewhat declarative" - given that the Python launch API is by far the most used and the amount of flexibilty that affords makes launchfiles hard/impossible to analyze at build time.

## Goals & Benefits

Work in progress...
