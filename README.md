# Image Processing Activities 🐣 👋🏻

<h2> 🚀 This repo is for my Image Processing CMPE362 lecture - Hands On Activities. 
You can run in Google Colab directly. 
Outputs are available in the .ipynb files.</h2>

Here is the topics of activities:

Activity-1 : Prepare and submit a Jupyter Notebook containing the code and
the result for reading and displaying an image that you choose.

Activity-2: Prepare and submit a Jupyter Notebook file containing the codes and the results for: • Reading a colored RGB image that you choose and
displaying its R, G and B channels.
• Converting the RGB image into HSV color space and displaying its H, S and V channels.
• Converting the RGB image into Lab color space and displaying its L, a, and b channels.

Activity-3: 
Read snow.png and display it.
• Convert the image into HSV color space.
• Display V channel and its histogram.
• Apply histogram equalization to the V channel and display the
histogram of the result.
• By using H and S channel from the original image and V channel
after histogram equalization, go back to RGB color space.
• Display the result

Activity-4: 
Read a colored image of your choice.
• Convert it into a gray-scale image and display the
result.
• Filter the gray-scale image using each of the
following filters.
• Display the result using a colormap other than gray.
• Display the absolute value of the result using a
colormap that you choose.
 
 Activity-5:
 Read the image rice.png and display it.
• Threshold the image and display the resulting
binary image.
• Apply dilation and erosion operations using a
structuring element that you choose

Activity-6:
Read an image of your choice and convert it into gray-scale image and display it.
Compute Fast Fourier Transform of the gray scale image and visualize its
magnitude by using log transform (logarithm of 1 + its absolute value).
Shift the FFT of the image to the center and visualize its magnitude by using log
transform (logarithm of 1 + its absolute value).
-> At this point, you should see the reason for shifting FFT to the center before
visualization (it becomes easier to see the low frequency details).
Inverse the shifting using ifftshift.
Convert back the image from the Fourier domain to the spatial domain using
Inverse Fast Fourier Transform.
Check and see that the image remains the same (after conversion from the spatial
domain to the frequency domain and back from the frequency domain to the spatial
domain).
-> Actually, the maximum of the absolute differences should be around 10^-13
