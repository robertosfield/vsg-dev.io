---
layout: page
title: Documentation
permalink: /documentation/
---

## VukanSceneGraph Tutorial

The goal of this tutorial is to teach developers how to use the VulkanSceneGraph effectively in their graphical and compute applications. The tutorial assumes developers have prior knowledge of using CMake and C++ to build and write applications.  Knowledge of scene graphs, real-time graphics and Vulkan is not assumed, though teaching real-time graphics and Vulkan at depth is beyond the scope of this tutorial, links to 3rd party resources for further learnning will be provided.

The tutorial is composed of series of presententations that are coupled with exercises so that developers can learn about each topic then test out what they have learned. The topics covered are:

1. [Introduction](vsgTutorial/01_introduction/presentation/Introduction.md) to Scene Graphs, Vulkan and VulkanSceneGraph
2. Memory management - smart pointers, Objects and Allocators
3. Vector maths - GLSL style vectors, matrices
4. Scene graph nodes - creating and setting nodes
5. Geometry and State - setting up rendering
6. Scene graph io - loading images and nodes
7. Viewer - creating application viewer
8. Traversals - how to traverse and operate on a scene graph
9. Threading - scene graph, viewer and io threading
10. Optimizaton - how to improve performance & low power consumption

## Reference documentation

* [VulkanSceneGraph](ref/VulkanSceneGraph/html/classes.html)
* [vsgXchange](ref/vsgXchange/html/annotated.html)
* [vsgImGui](ref/vsgImGui/html/annotated.html)

## Background design and development

* Design : [Design Principles & Philosophy](docs/Design/DesignPrinciplesAndPhilosophy.md)
* Design : [High Level Design Decisions](docs/Design/HighLevelDesignDecisions.md)
* Exploration Phase : [3rd Party Resources](docs/ExplorationPhase/3rdPartyResources.md)
* Exploration Phase : [Areas of Interst](docs/ExplorationPhase/AreasOfInterest.md)
* Exploration Phase : [Report](docs/ExplorationPhase/VulkanSceneGraphExplorationPhaseReport.md)
* PrototypePhase : [Workplan](docs/PrototypePhase/Workplan.md)
* PrototypePhase : [Report](docs/PrototypePhase/PrototypePhaseReport.md)

## Useful 3rd party links to information on Vulkan

* [Introduction to Vulkan, Algorithms for Real-Time Rendering Lecture, Summer Term 2020](https://www.youtube.com/watch?v=isbMMIwmZes)
* [Vulkanised-2021 presentations](https://www.khronos.org/events/vulkanised-2021)
* Vulkan Synchronization:
    - [Guide to Vulkan Synchronization](https://www.lunarg.com/news-insights/white-papers/guide-to-vulkan-synchronization-validation/)
    - [Synchronization2 Validation](https://www.lunarg.com/news-insights/white-papers/vulkan-synchronization2-validation/)
* Building a Vulkan Layer in Symbiose Within the Vulkan Ecosystem:
    - [Vulkan Layers](https://www.lunarg.com/wp-content/uploads/2021/09/Vulkan-Layer-Symbiosis-within-the-Vulkan-Ecosystem.pdf)
    - [Enhanced Devsim](https://www.lunarg.com/wp-content/uploads/2021/09/Enhanced-Devsim-15Sept2021.pdf)

