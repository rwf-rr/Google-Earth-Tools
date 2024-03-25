# BC Rail Takla Sub Tours

Google Earth "My Places" files for the CN (ex BC Rail) Takla subdivision (British Columbia, Canada).

The main KML file contains everything. The additional files are subsets, places, paths and tours.

The finished videos are available on ???.

## Settings

The basic settings for tours are in the `Tools --> Options --> Touring` menu, "when creating tour from a line". They apply to all tours.
I used the following settings:
- `Use 3D Imagery` is disabled. I found that there are a few areas that have bad 3D Imagery (not sure if this applies to the Takla sub area).
- `Camera Tilt Angle`: 80°
- `Camera Range`: 100 meters (this is the default; I did not experiment with it)
- `Speed`: 240 mph

Path Properties:
- `Altitude`: 20 meters above ground

There are no tour specific properties.

### Part 3: Dease Lake Extension

This section was graded, but no rail was ever laid. The area is very remote and has low-resolution satellite images. There is little ground-level detail.
Thus I took a different approach, using a higher altitude for the camera, showing an overview of the terrain, rather than the details of the "track".

This had the following impact:
- Needed two paths, one for the grade and one for the camera. From the higher altitude, the grade is not always easy to recognize.
- Camera needs to tilte a bit more towards the ground.
- Camera range needs to be a bit longer to track the higher path.
- Able to use much higher tour speed, as there was less detail to see.

Properties and Settings:
- Grade path properties: Altitude: `clamped to ground`. This makes it easier to capture and adjust the path.
- Camera (tour) path properties: `absolute`, `2200 meters`. Determined on reasonable views for low and high points.
- Touring settings: Camera Tilt Angle: `75 degree`; Camera Range: `200 meters`; Speed: `900 mph`. Finding a reasonable camera range is tricky.

## Notes

- Considered manually edited the path file, to deal with camera tracking issues at certain locations. However, I was able to get decent results with slightly modifying the path.
  * Increase the camera altitude, where the cliffs and sharp curves caused camera-collisions with the ground.
  * Increase the camera altitude and reduce the duration (increase speed), where the satellite image-resolution is low.
