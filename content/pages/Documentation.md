---
title: "Documentation"
date: 2023-05-12T09:28:00-05:00
draft: false 
---

## Introduction 

This is the documentation page for my CSC 2464 final project. There is information for the project outline, a brief description, schematics, and future ideas for the project. 

## Project Outline 

The idea for the project started with a simple addition to the painting app project of adding customizable colors with the use of an arduino board and potentiometers. The goal was to provide an alternative way to explore human-machine interactions.  


### Initial Plan 
 Originally, I had planned to make use of LED lights to provide a preview of colors as they are individually changed by the potentionmeter. Below is a rough draft of what I had planned. 

![Initial design](/pages/initial-design.png)

Although at the time it made sense, I decided to not go forward with the addition of LED to provide a preview since the project already provides a preview in the p5 canvas. I believed it added unnecessary complexity to the project but I did like the aspect of feedback. So insteda, I decided to add a simple LED light to indicate when the user is performing any activity with the app.  

### Final result

I decided to stick to a simpler design that made use of the of the arduino board to adjust the hue,saturation and brightness of the color. Initially, I had planned on using simple RGB but was advised that the HSB system would be a more humane way of dealing with color. 
Below is a video of me using the final design. If the video is cropped, make the video fullscreen.  
{{< video "/pages/videoDemo.mp4" "my-5">}}

Here's what the board and the pin placements looked like. The gap is due to potential features.
![final image](/pages/final-image.jpg)

## Future ideas 
Further additions can be added to the project in order to add more interesting functionality. One suggestion by my professors was the change of brush size through the use of movement through the bionic sensors that came in the arduino kit.

Another addition could be to provide joystick support to control the cursor through the use of fingers instead of a mouse. 

Both of these additions would enhance the experience of the project.  



