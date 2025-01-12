# Tessellation Settings (HDRP)
* [Tessellation Mode]
* [Tessellation Factor]
* [Start Fade Distance]
* [End Fade Distance]
* [Triangle Size]
* [Shape Factor]
* [Triangle Culling Epsilon]

### Tessellation Mode
Control the Phong tessellation. It can be used to smooth the result of displacement.
### Tessellation Factor
Controls the strength of the tessellation effect. Higher values result in more tessellation. Maximum tessellation factor is 15 on the Xbox One and PS4.
### Start Fade Distance
Sets the distance (in meters) at which tessellation begins to fade out.
### End Fade Distance
Sets the maximum distance (in meters) to the Camera where HDRP tessellates triangle.

### Triangle Size
Sets the desired screen space size of triangles (in pixels). Smaller values result in smaller triangle.

### Shape Factor
Controls the strength of Phong tessellation shape (lerp factor).

### Triangle Culling Epsilon
Controls triangle culling. A value of -1.0 disables back face culling for tessellation, higher values produce more aggressive culling and better performance.