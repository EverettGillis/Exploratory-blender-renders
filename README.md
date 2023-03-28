# Exploratory-blender-renders

**About**
\
\
Two experimental solid renders produced in a brief exploration of blender.

\
**Overview**
\
\
Interestingly, the same techniques used to integrate non-uniform 3D solids can be used to construct vertex frameworks in blender. Points may be plotted in space via a function dictating the dimensions of a slice of a solid relative to the position of the slice in the perpendicular axis, and the areas between the points filled to form connected faces. While greater numbers of points plotted result in constructs of higher resolution, native smoothing eliminates undesired ridges and reduces render time.

\
**Intended Use**
\
\
```framework.blend``` files include code for vertex frameworks and faces.<br/>
```render.blend``` files present smoothed renders.<br/>
```solid.png``` files show rendered objects.<br/>
Requirements: Blender 3.1.0, Python 3.10.
