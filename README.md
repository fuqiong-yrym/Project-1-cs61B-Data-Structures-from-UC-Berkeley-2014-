# Project-1-cs61B-Data-Structures-from-UC-Berkeley

This repository includes the partial solutions (part I) to project 1 of CS61B from UC Berkeley.  

The assignment is to implement two simple image processing operations on color images: blurring and edge detection.

Part I includes the following:

- Implement a class called PixImage that stores a color image
- Implement methods boxBlur() and sobelEdges()

The details of assignment requirement can be found in readme_project1.pdf

In Unix, run the command to complie against the JAI image libraries in the .jar files included:

   ```bash
   javac -cp "jai_core.jar:jai_codec.jar" *.java
   ```

The the main() methods in Java classes Blur.java and Sobel.java read an image in TIFF format, use the codes required in the assignment to perform blurring and/or edge detection, write the modified image in TIFF format, and display the input and output images.

   ```bash
   javac -cp java -cp ".:jai_core.jar:jai_codec.jar" Blur image.tiff 3
   javac -cp java -cp ".:jai_core.jar:jai_codec.jar" Sobel image.tiff 3
   ```

<p align="center">
  <img src="highcontrast.jpg" width=400 height=300> 
  <img src="blur_highcontrast.jpg" width=400 height=300>
  <img src="edge_highcontrast.jpg" width=400 height=300>
</p>
