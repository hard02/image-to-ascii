# image-to-ascii


This program is a Python script that takes an image file as input, converts it into an ASCII art representation, and outputs the result as text in the console and in a text file. 
The program uses the PIL library to open, resize, and convert images. You can install PIL or its successor Pillow using pip, the package installer for Python, by running the following command in a terminal or command prompt:


``` pip install pillow ```


The program first defines a list of ASCII characters that will be used to build the output text. It then defines three functions:

- resize_image(): resizes the input image to a new width while maintaining its aspect ratio.

- grayify(): converts each pixel of the input image to grayscale.

- pixels_to_ascii(): converts each pixel of the input image to an ASCII character based on its brightness level.

The main() function is then defined. It first prompts the user to enter the pathname of an image file. If the path is invalid, an error message is printed, and the program exits. If the path is valid, the program opens the image file using the PIL library, resizes it, converts it to grayscale, and converts its pixels to ASCII characters. It then formats the ASCII characters as a string with line breaks to create the final output text.
