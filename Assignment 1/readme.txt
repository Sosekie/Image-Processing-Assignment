# Full Name: Chenrui Fan

# Surname: Fan

# Link to My GitHub:

https://github.com/Sosekie/Image-Processing-Assignment

# Description of My Flipping Algorithm:

An image can be thought of as a matrix containing a large number of values, so it is possible to change the image by manipulating the matrix.

Here I am using numpy to transform the image into a matrix. If you want to flip the image horizontally, this means that the matrix swaps its left and right elements along the vertical axis of symmetry, in which case the vertical coordinates of the matrix remain unchanged, and the value of the element at [j] in the horizontal coordinate is the value of the element at [width - j - 1] in the original image.

If you want the image to be flipped vertically, this means that the horizontal coordinates of the matrix remain unchanged and the value of the element at [i] in the vertical coordinate is the value of the element at [height - i - 1] of the original image.

If you want to flip the image vertically and horizontally at the same time, just change the horizontal and vertical coordinates at the same time.