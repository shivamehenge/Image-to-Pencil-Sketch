# Image-to-Pencil-Sketch

LetsGrowMore (LGM) - Virtual Internship Program

Data Science Intern

Language - Python

IDE - Jupyter Notebook

Dataset : -https://thecleverprogrammer.com/2020/09/30/pencil-sketch-with-python/

We need to read the image in RBG format and then convert it to a grayscale image. This will turn an image into a classic black and white photo. Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image. Inversion can be used to enhance details. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.
