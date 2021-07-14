## General notes

## Canny Edges


### Hough Transforms
- Take a line of y=mx+b and plot it in a (m, b) space
- This (m,b) spatial layout is called Hough space
- The intersection of two lines in Hough space is an (m, b) value that corresponds to a line of y=mx+b, so in image space, all (x,y) values along that line can be thought of as being represented in the (m,b) point in Hough space
- Hough space can also be represented in polar coordinates of rho, theta (see google notes for this), because vertical lines have infinite slope (m value) in (m,b) coordinates, which isn't super helpful
  - Essentially, lines in image space look like intersection sin curves in Hough space 
