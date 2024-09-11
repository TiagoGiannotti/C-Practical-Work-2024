# C-Practical-Work-2023
<h1 align="center">
C Practical Work
</h1>
<h4 align="center">
Repository for the practical work of the Programming Topics course - UNLaM (National University of La Matanza).
</h4>

<p align="center">
    <a href="#----summary">Summary</a> •
    <a href="#----key-features">Key Features</a> •
    <a href="#----installation">Installation</a> •
    <a href="#----license">License</a> •
</p>

<h2>
    Summary
</h2>

  The task involves developing a C program named bmpmanipulator that processes a 24-bit BMP image file based on user-specified modifications provided as command-line arguments. The program should handle various image transformations, including:
  
-negative: Inverts the colors of the image.

-grayscale: Converts the image to grayscale by averaging the RGB values.

-increase-contrast: Enhances the contrast by 25%.

-decrease-contrast: Reduces the contrast by 25%.

-blue-tone: Increases the blue color intensity by 50%.

-green-tone: Increases the green color intensity by 50%.

-red-tone: Increases the red color intensity by 50%.

-crop: Reduces the image size by 50%, keeping the proportions intact.

-rotate-right: Rotates the image 90 degrees to the right.

-rotate-left: Rotates the image 90 degrees to the left.

-resize: Reduces the image dimensions to 50%, adjusting pixel locations accordingly.

-monochrome: Converts the image to 1-bit depth, representing each pixel as either black or white based on average RGB values.

The program must produce a modified BMP file for each operation, with the resulting files named appropriately. It should read and write BMP headers and pixel data accurately, ensuring proper image manipulation. The modifications should be implemented in the funciones_estudiante.h and funciones_estudiante.c files.


<h2>
    Key Features
</h2>
<p>
    <ul>
        <li>
            Flexible Image Transformation
        </li>
        <li>
            Command-Line Interface
        </li>
        <li>
            BMP File Handling
        </li>
        <li>
            Custom Output Naming
        </li>
        <li>
            Image Quality Management
        </li>
        <li>
            Detailed Documentation
        </li>
    </ul>
</p>

<h2>
    Installation
</h2>

 1. Clone the repository to your device and install the CodeBlocks IDE with MinGW.
 2. Open the files bmpmanipuleitor.cbp (main project) with the CodeBlocks application. These files are located within the cloned repository.
 3. Select the bmpmanipuleitor.cbp project (main project) and compile it in Release mode and Debug mode.
 4. Go to project, set program arguments and set the following arguments:
    
 .\TestImg.exe test_org.bmp --negativo --monocromo --achicar --gris --aumentar-contraste --recortar --rotar-derecha --rotar-izquierda --tonalidad-azul --tonalidad-roja --tonalidad-verde 

 ## Additional Material
-   [Practical Work Requirements](./.github/Requeriments.md)

<h2>
    License
</h2>
<p>
    This repository is under <a href="./LICENSE" target="_blank">MIT License</a>, if you want to see what you are allowed to do with the content of this repository, please visit <a href="https://choosealicense.com/licenses/" target="_blank">choosealicense</a> for more information.
</p>
