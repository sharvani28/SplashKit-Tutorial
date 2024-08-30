# Tutorial Proposal

## Title: Dynamic Camera Control with SetCameraPosition and ScreenRectangle

## Introduction

This tutorial aims to demonstrate the usage of the SetCameraPosition and ScreenRectangle functions in SplashKit. By the end of this tutorial, readers will learn how to implement dynamic camera movements and visual effects, allowing for interactive and immersive experiences in their projects.

## Prerequisites

To follow along with this tutorial, readers should have:

- Basic knowledge of programming concepts.
- Familiarity with the Splashkit library.
- Installed Splashkit (<<https://splashkit.io/installation/>) and set up their development environment.

## Functions Used

- [Screen Rectangle](https://splashkit.io/api/camera/#screen-rectangle)
- [Set Camera Position](https://splashkit.io/api/camera/#set-camera-position)

## Table of Contents

1. Tutorial Details

    - Tutorial Structure
    - Level of Difficulty

2. Examples

    - Example 1: Creating a Zoom Effect on a Clicked Area
    - Example 2: Following a Bitmap with User Mouse Clicks

## Tutorial Details

### Tutorial Structure

This tutorial provides step-by-step instructions on using SetCameraPosition and ScreenRectangle functions to control camera behavior and create dynamic visual effects.

### Level of Difficulty

This tutorial is aimed at intermediate programmers with some experience in graphics programming and the SplashKit library.

## Examples

- **Example 1: Creating a Zoom Effect on a Clicked Area**

  This example demonstrates how to use SetCameraPosition to zoom into a specific area of a 9x9 coloured grid when a box is clicked. The camera adjusts to focus on the selected box, filling the screen with its color.

- **Example 2: Following a Bitmap with User Mouse Clicks**

  In this example, we demonstrate how to use 'SetCameraPosition' and 'ScreenRectangle' to follow a bitmap as it moves in response to user mouse clicks. The bitmap, which represents a character or object in a game world, is initially loaded in the window. When the user clicks on the screen, the bitmap moves towards the clicked position. This showcases how to implement responsive camera controls that track an object's movement based on user interactions.

## Expected Learning Outcomes

After completing this tutorial, readers will be able to:

- Understand the purpose and usage of SetCameraPosition and ScreenRectangle Functions.
- Implement dynamic camera movements and zoom effects in their SplashKit projects.
- Create interactive and immersive graphical applications with responsive camera controls.

## Conclusion

This tutorial demonstrated how to use SetCameraPosition and ScreenRectangle to create dynamic camera movements and zoom effects in SplashKit. SetCameraPosition enables precise control over the viewable area, allowing for smooth tracking of objects or specific scenes. ScreenRectangle helps define and visualize the current viewport. Together, these functions enhance interactivity and immersion, enabling developers to build engaging and responsive graphical applications.
