# Automated-License-Plate-Readers(ALPRs)

This App leverages OpenCV and EasyOCR to analyze an image and extract the text within it.
There are 2 Images in the assets, or you can analyze your own (copy your image to the assets folder and target the name of your file)

```img = cv2.imread('assets/image2.jpeg')```

### Special instructions required for the Reviewer:

This Jupyter notebook was created in Visual Studio Code V1.72.2

Please Install and Import Dependencies listed below in the Terminal:

```pip install OpenCV```

```pip install EasyOCR```

```pip install imutils```

```pip3 install torch torchvision torchaudio```



######Feature 1: (Read Data in) 

>OpenCV2 to import Image into Python

######Feature 2: (Manipulate and clean your data) 

>OpenCV2 to PreProccess the Image, appling filters

######Feature 3: (Analyze your data) 

>Edge Detection to detect where the license plates are located in the image, mask out the license plate

######Feature 4: (Visualize your data) 

>easyOCR to Extract the license plate text
>
>Matplotlib to display the image on a graph


### Special Thanks to *Nicholas Renotte* and *CodeKY Mentors* for their Contributions.
