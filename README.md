# TAKE A TRIP! - Real-time Webcam "Datamosh"

![TAKE A TRIP! Screenshot](placeholder.png)

Dive into a world of psychedelic visuals with "TAKE A TRIP!" This web application uses your webcam feed and applies real-time trippy effects directly in your browser, powered by WebGL shaders.

## Features

*   **Real-time Effects:** Watch your webcam feed transform instantly.
*   **Interactive Controls:** Fine-tune the visual experience with intuitive sliders.
*   **Datamosh-inspired Trails:** Create ghostly trails and motion blurs.
*   **Record the Results:** Capture trippy videos to share.
*   **Dynamic Hue Shifting:** Cycle through vibrant colors.
*   **Motion Detection Effects:** Visuals react to movement.
*   **Frame History Blending:** Blend past frames for temporal distortions.
*   **Frame Freezing:** Capture and loop interesting visual moments.
*   **Randomize Effects:** Discover new visual combinations with a single click (Hue & History sliders are excluded for stability).
*   **Responsive UI:** Controls are usable on various screen sizes.

## Controls Explained

*   **Trail:** Adjusts the persistence or "ghosting" of previous frames. Higher values create longer trails.
*   **Motion:** Sets the threshold for motion detection. Lower values make the effects more sensitive to small movements.
*   **Hue:** Controls the speed of the hue cycling effect.
*   **History:** Determines how many past frames are blended into the current view, creating layered effects.
*   **Extrap:** Influences motion extrapolation, adding a smearing or predictive motion effect.
*   **Freeze Frame:** Captures the current visual state and loops it. You can stack multiple frozen frames.
*   **Clear Frozen:** Clears any frozen frames and returns to the live webcam feed.
*   **Randomize Sliders:** Randomly sets values for Trail, Motion, and Extrap sliders to quickly discover new effects.

## Stack

*   HTML5
*   CSS3
*   Vanilla JavaScript
*   WebGL (GLSL for shaders)

## To-Dos

*   More diverse shader effects.
*   Audio reactivity.
*   Ability to save and load presets.

---

Feel free to fork!
