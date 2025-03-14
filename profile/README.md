# Robograph Project

Robotics software application declarative graph metaproject, focused primarily on ROS 2.

## Motivation

Allow us to declare the interfaces and structure of our ROS 2 applications, just as we might do with [library interfaces](https://en.cppreference.com/w/cpp/language/modules), [web APIs](https://www.openapis.org), or [system configuration](https://nix.dev/manual/nix/2.24/).

The current default model of imperatively created dynamic applications, while useful for its flexibility, allows for many types of misconfiguration that can't be caught until runtime, and make the application difficult to reason about at a high level, manually or with automated tooling. 

This organization exists to track new development and useful tools that meet its goals:
- Reduce application boilerplate for creation of Parameters, Topics, Services, Actions, and Nodes: Let you focus on the robotics!
- Catch misconfiguration errors early in the build process rather than at runtime
- Autogenerate usage documentation for ROS Nodes and "application subsystems"
- Enable runtime health monitoring and error reporting for full ROS 2 applications
- Recommend best practices for development

## Get Involved!

The best way to get started is to head over to [the docs repository](https://github.com/robograph-project/docs) and [join the discussion](https://github.com/orgs/robograph-project/discussions). 

This projlect is early days and we're looking for community input to help figure out priorities.

