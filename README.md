# Elliptical Orbit Simulation

This simulation models the motion of a body orbiting a star along an elliptical path, illustrating Kepler's second law.

Access the simulation on p5.js [here](https://editor.p5js.org/saphiooo/sketches/14yGmg-Q0).

## How to Use

1. Open the simulation via the link above.  
2. Set the orbital parameters to experiment with different types of orbits in the code editor on the left. Variables that can be changed include
   - Eccentricity of the orbit, with 0 being a circle, and 1 being a line.
   - Trail length of how many dots to plot after the main orbiting body.
   - DeltaT, or the area the planet will sweep out at each step.
   - Delay between steps or increments of the simulation.
   - Planet size and sun (star) size in pizels.
   For instance, an example setup is:
    ```javascript
    // The following variable is the eccentricity of the orbit.
    // An eccentricity of 0 is a circle, while an eccentricity of 0.9 is a
    // narrow ellipse.
    let eccentricity = 0.39;
    
    // The following is how many trailing dots to plot.
    let TRAILLENGTH = 10;
    
    // This is how much of an area the planet will sweep out at each step.
    let DELTA_T = 5000;
    
    // This is how much to delay the simulation between steps.
    let DELAY = 20;
    
    // This is the planet size in pixels.
    let planetSize = 5;
    
    // This is the sun size (focus) in pixels
    let sunSize = 30;
    ```
3. Run the simulation by clicking the Run button in the top right.

## Credits
This project was originally written for Processing by [Jason Galbraith](https://github.com/jasongalbraith). 

It was rewritten for p5.js by [Sophia Wang](https://github.com/saphiooo).
