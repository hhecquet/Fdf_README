# Fdf

> [!IMPORTANT]
> None of my code is publicly available here, but if you're a recruiter, I'd be happy to share it with you upon request.

<p align="center">
<img width="317" height="268" alt="Screenshot from 2025-07-23 08-57-06" src="https://github.com/user-attachments/assets/bfae2c73-7a26-403d-acda-06b6cd9f967a" />
</p>

The ***Fdf*** project is a graphical programming assignment at 42 where I created a wireframe 3D representation of a map using C. The input is a simple text file with elevation data, and the goal is to render this in a 2D window with an isometric projection — simulating a 3D view.
This project introduced me to computer graphics fundamentals, matrix transformations, projections, and pixel manipulation using a minimal graphical library (usually MiniLibX).

What I had to do:
* Parse a map file consisting of rows of numbers representing elevation
* Store this data in a structured way using dynamic memory allocation
* Implement **Bresenham’s line drawing algorithm** to connect points
* Apply isometric projection to simulate 3D depth on a 2D plane
* Create a window and draw the map using the **MiniLibX** library
* Add zooming, panning, and height scaling capabilities
* To accomplish this, I had to:
  * Convert 3D coordinates (x, y, z) to 2D screen positions
  * Handle different keyboard inputs to control the view (e.g., movement, zoom)
  * Manage efficient screen redraws and window events
  * Ensure correct scaling and centering of the map regardless of size

Bonus Part: Visual Enhancements
* For the bonus part, I extended Fdf with:
* Color gradients based on altitude values to improve depth perception
* Dynamic projection switching (e.g., between isometric and parallel views)
* Mouse controls for more interactive map navigation
* Smooth scaling and rotation features for a better user experience

What I Learned:
* Fundamentals of computer graphics and 3D-to-2D projection
* Implementing Bresenham’s algorithm for pixel-perfect line drawing
* Working with **MiniLibX** to handle graphical output and events
* Handling large data sets and transforming them into visual representations
* Building an interactive, visually responsive program in C
* Debugging graphical artifacts and optimizing redraws

Fdf was my first hands-on experience with graphics programming. It sharpened my understanding of geometry, math in programming, and how graphical applications are structured at a low level. It was both challenging and rewarding to watch raw data come to life as a fully navigable 3D landscape.

<img width="1917" height="1081" alt="Screenshot from 2025-07-23 14-43-48" src="https://github.com/user-attachments/assets/cb2d7887-d0c0-4f15-a524-4ff6ad052b58" />
