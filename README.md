# SafeWorld window display

An interactive poster for a storefront window. A robot arm moves a heap of parts from one tray to
another, slows down as someone walks up, stops when they are close, and reacts to them: it looks at
you, nods, waves back and more. The parts are simulated, so they tumble and pile up on their own.

Open it: https://miraj212.github.io/safeworld-window-display/

## Trying it

- With no camera, the page runs a demo. Move the mouse over the poster to play the passerby, and
  click to wave.
- Press **Use my camera** to have it react to you. The video is analysed in your browser and is
  never uploaded or stored.
- **Setup** holds the distances, the camera angle and a button for each of the robot's moves.
  Press **H** to hide the controls.

## Credits

- Robot model: Franka Emika Panda from
  [MuJoCo Menagerie](https://github.com/google-deepmind/mujoco_menagerie), Apache-2.0.
- 3D drawing: [three.js](https://threejs.org), MIT.
- Physics for the parts: [cannon-es](https://github.com/pmndrs/cannon-es), MIT.
- Person and pose detection: [MediaPipe](https://developers.google.com/mediapipe), Apache-2.0.
