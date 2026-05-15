# Histogram Equalization Using OpenCV for Grayscale and Color Images

## Aim

To develop a Python program using OpenCV that performs histogram equalization on both grayscale and color images in order to improve image contrast and overall brightness.

The program includes the following tasks:

- Load and display a grayscale image
- Generate the histogram of the grayscale image
- Enhance the grayscale image using histogram equalization
- Load and display a color image
- Plot histograms for the Blue, Green, and Red channels
- Convert the color image from BGR to HSV color space
- Perform histogram equalization on the Value (V) channel
- Convert the enhanced HSV image back to BGR format
- Display both original and enhanced images along with their histograms

---

## Software Requirements

- Python 3.7 (Anaconda Distribution)
- Jupyter Notebook / VS Code
- OpenCV (`cv2`)
- NumPy
- Matplotlib

---

## Algorithm

### Step 1
Import the necessary Python libraries such as OpenCV, NumPy, and Matplotlib.

### Step 2
Read the image file `parrot.jpg` in grayscale mode.

### Step 3
Display the grayscale image and plot its intensity histogram.

### Step 4
Apply histogram equalization using the `cv2.equalizeHist()` function to enhance image contrast.

### Step 5
Display the original grayscale image, its histogram, the enhanced image, and the histogram of the enhanced image using a 2 × 2 subplot arrangement.

### Step 6
Read the same image in color mode.

### Step 7
Separate the image into Blue, Green, and Red channels and plot the histogram for each channel.

### Step 8
Convert the color image from BGR color space to HSV color space.

### Step 9
Perform histogram equalization on the Value (V) channel to improve brightness and contrast.

### Step 10
Merge the HSV channels and convert the enhanced image back into BGR format.

### Step 11
Display the original color image, corresponding histogram, enhanced image, and enhanced histogram using a 2 × 2 layout.

---

## Program

### Developed By
### **Name:** udhaya prakash v

### Register Number : 212224240177

---

## Output

### Grayscale Image Enhancement

- The original grayscale image is displayed
- Histogram of the original grayscale image is generated
- Enhanced grayscale image after histogram equalization is displayed
- Histogram of the enhanced image shows improved contrast distribution

### Color Image Enhancement

- The original color image is displayed
- Histograms for the B, G, and R channels are plotted
- Enhanced color image after HSV-based equalization is displayed
- Histogram of the enhanced image demonstrates improved intensity spread

---

## Result

Thus, histogram equalization has been successfully implemented on both grayscale and color images using OpenCV. The enhancement process improves image contrast, brightness, and overall visual appearance, making image details more clear and distinguishable.
