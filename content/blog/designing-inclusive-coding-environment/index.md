---
title: "Designing an Inclusive Coding Environment"
date: "2020-05-12"
---

# Designing an Inclusive Coding Environment

{{< img src="images/Coding Environment Scene with Grid.png" alt="Coding Environment Scene with Grid." >}}

The Coding to Learn and Create project’s Inclusive Coding Environment is being designed based on the insights gleaned from a continuing series of co-design activities with learners with disabilities, their families, educators, and the inclusive design community at the IDRC. In each of these activities, we have had an opportunity to try out different ideas for the coding environment with our co-designers and work together to find out how we can make them more accessible and inclusive of diverse needs. 

One of the main lessons learned from our co-design activities is that each learner is unique and their needs are constantly changing as they learn. To be able to build a program that can address this diversity, we need a coding environment that is flexible and customizable so that teachers, parents, and students can choose the parts they want to use. To reflect this in our work, we have designed a user interface that is made up of self-sufficient parts that each have a specific purpose. Each part also contains subcomponents that can be easily customized to the learner’s skill level and needs. With this approach, learners and their teachers can have full control of what parts of the user interface are available, and they can decide what level of difficulty or complexity they want to support. Here you can see two different configurations of the main panels in the user interface—one version designed for controlling on-screen characters, and another optimized for use with robots in the physical environment of the classroom.

{{< img src="images/Coding Environment Simplified View.png" alt="Coding Environment Simplified View." >}}

Our coding environment is built around a storytelling metaphor. Learners can create their own creative stories using code, or act out scenes and goals in someone else’s story. We’d like to build an environment that supports children with complex learning needs to express their imagination, stories, and experiences through code. We consider a story as the complete state of an on-screen world—including all scenes, characters, and behaviors within it, as well as supporting “hybrid” stories that include off-screen robots and other physical activities. Every element in our design should enable users to create a story, such as building a scene, creating a character, and assigning specific goals and behavior to their characters. 

The Inclusive Coding Environment’s user interface is made up of five main panels, as specified in the following image. The appearance and the functionalities of each panel is customizable. Here is a brief description about how each panel contributes to the creation of stories. 

{{< img src="images/Coding Environment Default View.png" alt="Coding Environment Default View." >}}

### 1. The Scene

This is the stage for the story. The background and the characters are displayed on the scene. Once a program is played, the characters will perform the program on the scene. Users can scroll both vertically and horizontally to navigate the scene.  When the environment is used with physical robots rather than virtual characters, the scene can function as a kind of preview for how the robot will move and behave. 

### 2. Backgrounds

Users are able to select from a collection of already built backgrounds, edit them, or build their own. Only one background can be selected at a time and displayed on the scene. Backgrounds are static images and don’t interact with the characters. 

### 3. Characters

Users can select from a collection of already built characters, edit them, or build their own. They can add as many characters as they want to their scene. Users can decide whether a character is static or dynamic. Dynamic characters are interactive and users can build a program and assign specific actions and behaviors to them. Static characters are not programmable. They can place their characters anywhere on the scene and adjust its visual appearance, such as size, direction, and transparency. Each character can also perform as an avatar for robots that are connected to the coding environment. 

{{< img src="images/Coding Environment Scene.png" alt="Coding Environment Scene." >}}

### 4. Actions

Actions are the essential elements for bringing a story to life. They help users build a specific behavior for their characters, plan a mission, move a character, build a game, indicate a condition, etc. The action panel is made up of a wide range of different options, such as movements, sounds, controls, and events. Users can customize this panel and configure the number of available options for building a story. To not limit users imagination, we have included a “Custom Tile” function that enables users to build custom actions and behaviors.

### 5. Program

In the program area, users can use the available actions from the “Actions” panel to build a narrative or plan a course of actions for their dynamic characters. Each dynamic character has its own program area consisting of program rows. Users can add as many program rows as they wish for a dynamic character and create specific activities and assign unique behaviors and conditions to their characters. The program rows make the program area compatible with different assistive technologies, such as screen readers. 

{{< img src="images/Coding Environment Program Builder.png" alt="Coding Environment Program Builder." >}}

## Areas for further exploration

As we envision and design the C2LC coding environment, we encounter new areas that need further thinking and investigation. Here are two areas that are evolving in parallel with our design work:

### Terminology

The coding environment’s future design includes a greater set of features and functionalities that each require a unique name. The development and design teams are working together to build a glossary of terms that can be used across the coding environment. Our main criteria for selecting names is to make sure they are clear, easy to understand, consistent with other coding environments, and scaffolding for future coding education. 

### Errors States

Future designs will allow for more advanced coding configurations, such as events, conditional statements and repeating patterns. As a result, users can build an infinite number of different combinations, which will make the coding environment more prone to errors. The design and development team are working together to consider a wide range of edge case scenarios and explore different types of potential errors. We are also investigating other coding programs developed for kids to understand how they respond to an error state and what we can learn from them. This investigation will inform our design decisions and help us consider a variety of built-in constraints that minimize errors and user frustration and confusion. 