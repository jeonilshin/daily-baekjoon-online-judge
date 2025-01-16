# Little Prince

# Explanantion

The core of this problem is "Don't be misled by the diagram."
When I first looked at the diagram, there seemed to be too many possible methods, so I couldn't properly understand the problem.
However, in the case of the second input example, it became clear that drawing a diagram would involve too many and too large numbers. This means we need to use a mathematical formula instead of relying on the diagram.

When there is one circle and two points, there is only one case where the two points enter/exit the circle. That is when the first point is inside the circle, and the second point is outside the circle.

At this point, whether a point is inside the circle can be determined by the distance between the circle's center and the point:

- If the distance is less than the radius, the point is inside the circle.
- If the distance is greater than the radius, the point is outside the circle.