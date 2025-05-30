We want to isolate a color in an image, Define a range of colors and then apply a mask to the image, Isolating colors in OpenCV is straightforward. First we convert an image into HSV (hue, saturation, and
value). Second, we define a range of values we want to isolate, which is probably the most difficult and
time-consuming part. Third, we create a mask for the image (we will only keep the white areas).
