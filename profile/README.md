# Robograph Project

Metaproject pushing for and tracking work towards a declarative model for specifying robotics software applications.

Focused primarily on ROS 2.

## Motivation

Allow us to declare the interfaces and structure of our ROS 2 applications, just as we might do with [library interfaces](https://en.cppreference.com/w/cpp/language/modules), [web APIs](https://www.openapis.org), or [system configuration](https://nix.dev/manual/nix/2.24/).

The current default model of imperatively created dynamic applications, while useful for its flexibility, allows for many types of misconfiguration that can't be caught until runtime or with extensive integration testing.

These patterns make the application inherently difficult to reason about at a high level.

This project tracks new development and useful tools that meet these goals:

- Reduce application boilerplate for creation of interfaces (Parameters, Topics, Services, Actions, and Nodes). Let developers focus on the robotics!
- Catch misconfiguration errors early in the development process
- Autogenerate usage documentation for ROS Nodes and "application subsystems" (launch files)
- Enable runtime health monitoring and error reporting for full ROS 2 applications
- Recommend best practices for development

## Get Involved!

The best way to get started is to head over to [the docs repository](https://github.com/robograph-project/docs) and [join the discussion](https://github.com/orgs/robograph-project/discussions). 

This project is early days and we're looking for community input to help figure out priorities.

