# intersectionCircleLine
Geometrically, this function is able to find the intersection point(s) between a circle and a line.
- The function is written in JavaScript.
- It works fine using projected cartesian coordinates.
- it is is able to discern among different meet. I mean,
 - Circle and Line don't intersect
 - Line is tanget to the Circle
 - Line crossess the Circle

Al  what you need is to pass these arguments: x1, y1, x2, y2, Cx, Cy, Cr
- x1: _first point which defines the line. Coordinate X_
- y1: _first point which defines the line. Coordinate Y_
- x2: _second point which defines the line. Coordinate X_
- y2: _second point which defines the line. Coordinate Y_
- Cx: _center of the circle. Coordinate X_
- Cy: _center of the circle. Coordinate Y_
- Cr: _radius of the circle_

If the line crosses the circle, then you'll get both intersection points in F and G.
