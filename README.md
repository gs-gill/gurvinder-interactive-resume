# Gurvinder Singh Gill — Interactive Portfolio

A small, self-contained driving portfolio inspired by playful 3D portfolio sites. Explore the illustrated park, drive to career markers, and open résumé details at each stop.

## Run locally

Open `index.html` in a current browser, or serve this folder with any static web server. It is ready for GitHub Pages and needs no build step, framework, or third-party asset downloads.

## Controls

- Drive with **W/A/S/D** or the **arrow keys**. Forward accelerates, left/right steer, and reverse slows the car.
- Press **E** or select **Explore nearby** when beside a marker.
- Use **Map** or press **M** to jump to a stop. **Menu** lists every résumé section.
- On touch screens, use the on-screen arrow pad.
- Toggle the quiet engine tone with the sound button; click it again to mute.
- Download the original PDF from the About, Contact, or Menu panel.

## Implementation

The page uses native HTML, CSS, Canvas 2D, and a small inline JavaScript game loop. The scene, car, roads, buildings, map, responsive controls, and résumé panels are drawn or rendered locally. There are no runtime dependencies or external network requests.

The original `resume_2023.pdf` is included as a printable résumé.
