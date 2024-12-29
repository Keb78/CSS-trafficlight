Traffic Light CSS Project

Overview

This project is a pure CSS simulation of a traffic light system, designed to replicate the look and feel of a realistic traffic light. The design features a pole structure, a lightbox, and animated lights that switch between red, yellow, and green in a timed sequence. The background includes multiple gradients and an optional background image to enhance the overall aesthetics.

Features

Realistic Traffic Light Simulation - Red, yellow, and green lights animate in sequence using keyframe animations.

CSS-Only Design - No JavaScript required for functionality.

Customizable - Easily change the colors, dimensions, and animations to fit different design requirements.

Gradients and Shadows - Utilizes linear and radial gradients for a polished and modern appearance.

Upcoming Features

Fully Responsive Layout - Adjustable to different screen sizes.

File Structure

/css-project |-- index.html # Main HTML structure (Optional, to be created by user) |-- style.css # Core CSS styling (This file) |-- pexels-photo-1707820.jpeg # Background image (Optional)

How It Works

Background Styling:

A combination of linear and radial gradients creates a layered background effect.

The optional background image blends seamlessly with the gradients.

Pole Construction:

.Pole-vertical and .Pole-horizontal replicate the vertical and horizontal parts of the pole.

Shadows and gradients simulate the metallic look.

Traffic Light Box:

.Box acts as the container for the lights.

Lights:

.Light forms the base for the red, yellow, and green light containers.

The lights (.Redbox, .Orangebox, .Greenbox) use radial gradients and box shadows to create glowing effects.

Animation:

Keyframes (switchOnSequentialRed, switchOnSequentialOrange, switchOnSequentialGreen) control the timing of the light transitions.

Lights sequentially fade in and out to simulate real traffic light behavior.

Usage

Clone or download the repository.

(Optional) Replace the background image with your own by updating the url path in the body selector.

Customization

Change Light Duration: Modify the animation-duration property in the @keyframes section to adjust how long each light stays on.

Pole and Box Dimensions: Adjust the width, height, and margins in .Pole-vertical, .Pole-horizontal, and .Box to resize the pole and traffic light box.

Light Colors: Customize the radial gradient colors in .Redbox, .Orangebox, and .Greenbox to match your design preferences.

Credits

Background image: Pexels

Design and implementation by Keb Andrew Derian

License

This project is licensed under the MIT License - feel free to modify and distribute as needed.
