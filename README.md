# Interactive **Conductor Loop**

This program provides two conductors where the current and its direction can be set, as well as the shape.
By pressing CTRL while moving a point, the mirrored point on the other conductor is moved too.
Pressing ALT and the middle mouse button resets the zoom applied by the mouse wheel. Holding the wheel, the chart can be dragged.

The calculation is numeric utilizing the Biot-Savart-law. Between each node 1000 calculation points are set.

**IMPORTANT:** The calculation starts at the first node and ends at the last node.\
**IMPORTANT:** Changing the radius resets the shape to a circle.\
**IMPORTANT:** Toggling the linear/spline mode resets the shape to a circle.\
\
\
The project is written in Python and packed with pyinstaller.
