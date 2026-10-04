# Decisions
- **Why model-viewer?** It is a Google web component that handles rotate/zoom for 3D models, so I could focus on the page, controls and responsiveness.
- **Info points:** I used buttons that move the camera and show text, because they work on any model (hotspots need exact coordinates for each model).
- **Responsive design:** a flex column on mobile and a row on screens wider than 800px.

## One challenge and how I solved it (EDIT with your real experience)
Restarting the fade-in animation on every button click: the CSS animation only plays once, so I reset the element's animation in JavaScript before each change.
