# Playlist Builder

## Live Demo

https://rodrigomzanetti.github.io/Playlist-Builder/

## Preview

![Project Screenshot](./images/Screenshot.png)

## Overview

Playlist Builder is a simple front-end application that allows users to create and manage a music playlist through a form interface. Songs are dynamically rendered in the interface using an HTML template and JavaScript DOM manipulation.

The project focuses on practicing template cloning, form handling, and dynamic UI updates in a clean and modular way using vanilla JavaScript.

## Features

- Dynamic rendering of songs from an array (`initialSongs`)
- DOM manipulation using HTML templates (`<template>`)
- Form handling using `submit` events and `preventDefault()`
- Dynamic UI updates when new songs are added
- Automatic clearing of form inputs after submission
- Conditional UI state management for empty playlist message

## Technologies Used

- HTML5 – semantic structure and template usage
- CSS3 – layout and visual styling
- JavaScript (Vanilla JS) – DOM manipulation and dynamic behavior

## Project Structure

Playlist-Builder/

- index.html – main application markup
- style.css – project styles
- script.js – JavaScript logic and DOM interactions
- images/ – project assets

## How to Run the Project

- Clone the repository
  git clone https://github.com/RodrigoMZanetti/Playlist-Builder.git

- Navigate to the project folder
  cd Playlist-Builder

- Open the project
  Open **index.html** in your browser or run a local server if preferred.

## Status

- Completed as part of front-end development training.

## Problem Solving

- One of the main challenges in this project was dynamically rendering song cards while keeping the code reusable and easy to maintain. This was solved by using the HTML `<template>` element and cloning its content when new songs are added.

- Another challenge involved managing the empty playlist state. The interface needed to display a “No songs added” message until at least one song existed. This behavior was controlled through conditional DOM updates and CSS class toggling.

## What I Learned

During this project I practiced:

- Working with the HTML `<template>` element
- Dynamically rendering content using JavaScript
- Handling form submissions with event listeners
- Managing UI state using DOM class manipulation
- Writing reusable functions for DOM updates

## Author

GitHub  
https://github.com/RodrigoMZanetti

LinkedIn  
https://www.linkedin.com/in/rodrigomaturanozanetti/
