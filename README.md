Modal Window Project
A simple modal window project built using HTML, CSS, and JavaScript. This project demonstrates how to create and manage modal windows that appear when a button is clicked and disappear when a close button, overlay, or the Escape key is pressed.

## Introduction

This project showcases the functionality of a modal window which can be triggered by a button click. The modal can be closed either by clicking a close button, clicking on the overlay, or by pressing the Escape key. The project serves as a basic exercise in DOM manipulation using JavaScript and styling using CSS.

## Features

Open the modal by clicking a button.
Close the modal by:
Clicking the close button.
Clicking outside the modal (on the overlay).
Pressing the Escape key.
Lightweight and simple design, with reusable code.

## Technologies Used

HTML5: Structure of the modal and buttons.
CSS3: For styling the modal, buttons, and overlay.
JavaScript (ES6): For handling modal opening and closing behavior.
Getting Started
Installation
Clone the repository:

`bash
git clone https://github.com/yourusername/modal-window-project.git`
Navigate to the project directory:

`bash

cd modal-window-project `Open the project: Open`index.html` in your browser to see the modal in action.

## Usage

To open the modal, click on any button with the .show-modal class.
Close the modal by:
Clicking the X close button.
Clicking outside the modal (on the overlay).
Pressing the Escape key on your keyboard.

## File Structure

modal-window-project/
│
├── css/
│ └── styles.css # Contains all the styles for the modal and page layout
│
├── js/
│ └── script.js # Contains the JavaScript to handle modal behavior
│
├── index.html # The main HTML file with modal structure and buttons
└── README.md # This README file

## How It Works

The modal is initially hidden using the .hidden class, which applies display: none; to the modal and overlay elements.
When a button with the .show-modal class is clicked, JavaScript removes the .hidden class from the modal and overlay, making them visible.
The modal can be closed by:
Clicking the close button (which adds the .hidden class back to the modal and overlay).
Clicking the overlay area outside the modal (which also adds the .hidden class back).
Pressing the Escape key, detected by a keydown event listener that checks if the modal is open and closes it.
