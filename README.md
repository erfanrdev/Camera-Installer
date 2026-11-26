Camera Installer Assistant

A small single-file web app (Persian, RTL) that helps CCTV installers sketch a floor plan, place cameras, and send a quick summary to a customer.

Features
Create a room from width and length (in meters), then drag the corners to reshape it
Place cameras (bullet, dome, turret, PTZ), drag them around and rotate them
Field-of-view cone drawn to scale, clipped to the room so blind spots are visible
Image quality zones inside each cone (identification, recognition, observation, detection), based on pixel density (250 / 125 / 62 px/m) and computed from megapixels and FOV. Distances can be overridden per camera
Summary table with camera counts by megapixels and type
Export a PNG with the plan, camera table and date, ready to share
Usage

Open camera-planner.html in any modern browser. No build step, no dependencies.

The project is saved automatically in the browser's localStorage (one project per browser).

Limitations
One project at a time, no backend
Fixed camera presets
No obstacles or interior walls
PNG export only
Quality zones are estimates and assume a 16:9 image
License

MIT
