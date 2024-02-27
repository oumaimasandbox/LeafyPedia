# LeafyPedia
 Developed 'LeafyPedia', a MATLAB application for plant health analysis, utilizing image segmentation to diagnose and monitor plant health, catering to plant enthusiasts and experts.
 # Why have a leaf detection application
  The identification and diagnosis of plant diseases or infections can be a complex and time-consuming process.
  This requires expertise in plant pathology, access to specialized equipment and in-depth knowledge of the different diseases.
  By providing clear and accurate results on the health status of the leaves, Leafypedia helps users make informed decisions. They can decide on the measures to be taken, such as     the application of appropriate treatments or the quarantine of infected areas. This helps to optimize agricultural practices and minimize losses.
# Description of the project

The project consists of a MATLAB application developed using Of the App Designer tool. The application offers a graphical interface Allowing users to perform the following tasks:Import a sheet image: The user can select a leaf image from his computer using a box of File selection dialog. The selected image is then Displayed in the application.

leaf segmentation: Once the image is imported, the application Performs a segmentation of the sheet to isolate the region of theleaf to be analyzed. Segmentation is achieved by convertingThe RGB image in HSV color space, by extracting the channel of Saturation, by applying a threshold to create a mask Binary, and by performing morphological operations for

Improve the mask. Segmentation is also done using GraphCut tool that allows the user to select Analysis of the health status of the sheet: Once the segmentation Carried out, the application analyzes the health status of the sheet in Calculating the percentage of domination of green tones in the leaf. If the percentage of green exceeds a predefined threshold, the sheet Is considered healthy. Otherwise, the application analyzes the intensity Of each color channel (red, green, blue) to differentiate theHealthy leaves of infected leaves. If an infection is detected, The application calculates the percentage of infection and highlightsPotentially infected regions in red in the image Segmented.
# introduction to our app 

<img width="468" alt="Screenshot 2024-02-27 at 10 42 07 PM" src="https://github.com/oumaimasandbox/LeafyPedia/assets/77903484/c3e88c62-00bd-42ff-a4bf-39a9aede7057">

<img width="340" alt="Screenshot 2024-02-27 at 10 42 35 PM" src="https://github.com/oumaimasandbox/LeafyPedia/assets/77903484/1ea2d599-581c-48ed-af79-daa04e12f87d">

<img width="467" alt="Screenshot 2024-02-27 at 10 42 48 PM" src="https://github.com/oumaimasandbox/LeafyPedia/assets/77903484/a896b295-560f-4f28-8d6a-fa9fceba8486">
