# Procedural Image Reconstruction
This repository contains code for a procedural image reconstruction technique implemented in Unity 3D using a genetic evolution algorithm and compute shaders. The algorithm allows you to generate reconstructed images based on input images using genetic evolution techniques.

## Introduction
The project implements a genetic evolution algorithm to reconstruct images by evolving a population of brush strokes. Each brush stroke in the population has various properties such as position, color, size, and opacity. The algorithm uses a fitness function to evaluate the similarity between the generated image and the target image. Through a process of selection, crossover, and mutation, the algorithm evolves the population over multiple generations to converge towards an image that resembles the target.

## To use this project and generate your own reconstructed images, follow these steps:

* Download and install Unity 2019.1.14f1 & higher.
* Open Unity and create a new project.
* Ensure that your input image is in a square format and has dimensions that are a power of two (e.g., 1024x1024).
* Drag and drop your input image into the "Image to Reproduce" property in the "Evolution Manager" component attached to the "Manager" GameObject in the scene.
* Adjust the maximum image size and wrap mode properties of the image in Unity's inspector as necessary.
* Choose a run setting from the provided presets or create your own settings.
* The run setting determines the duration and level of detail for the image reconstruction.
* If you experience performance issues, you can adjust the population pool number in the settings.
* Press the play button in the Unity editor to start the image reconstruction process.
* Monitor the progress in the Game Window and check the console for real-time information.
* The current stage value indicates the progress, with 0 indicating the completion of the reconstruction.

## Demonstration
![BlackAndWhiteProtrait](https://github.com/viv3k19/Procedural-Image-Reconstruction/assets/82309435/30533dde-62db-4bf4-ac09-5fb73b6b45e2)

## Algorithm

* Utilizes a genetic evolution algorithm to generate paintings.
* Evolves a population of brush strokes.
* Each brush stroke has properties such as position, color, size, and opacity.
* Evaluates the similarity between the generated image and the target image using a fitness function.
* Performs selection, crossover, and mutation operations.
* Evolves the population over multiple generations.
* Aims to converge towards an image that resembles the target.

## Functionality
The project allows users to generate paintings based on their own input images. Users can drag and drop their images into the Unity editor and adjust settings such as image size and wrap mode. They can choose from preset run settings or create their own, which determine the duration and level of detail for the image reconstruction. The painting process can be monitored in real-time in the Game Window and the progress can be tracked through the console.

## Users
This project is suitable for artists, designers, or anyone interested in generating unique and procedurally created paintings. It provides a creative tool for exploring the potential of genetic evolution algorithms in the realm of digital art.

## Modules
The key modules of this project include:

* Genetic Evolution Algorithm: Implements the core algorithm for evolving the brush strokes population.
* Compute Shaders: Utilizes compute shaders for parallel processing and optimizing the evolution process.
* Evolution Manager: Acts as the control center, managing the evolution process and settings.
* Image Importer: Allows users to import their own images to serve as targets for the painting generation.

## Technologies
* Developed in Unity 3D.
* Utilizes compute shaders for efficient computation.
* Compatible with Unity version 2019.1.14f1 & higher.
* Primarily tested on Windows platforms with DirectX11.
* Supports OpenGL 4.5, but platform differences may occur.
* Well-documented codebase with insights into implementation details.

## Conclusions
Procedural Painting Using Genetic Evolution Algorithm in Unity 3D with Compute Shaders offers a powerful tool for generating unique paintings through an evolutionary approach. The combination of genetic evolution algorithms, compute shaders, and Unity provides a versatile platform for exploring artistic creativity and generating visually compelling artwork. By adjusting the algorithm parameters and experimenting with different input images, users can unlock a wide range of artistic possibilities and achieve captivating results.

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.
