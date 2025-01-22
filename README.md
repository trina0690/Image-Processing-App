# Image Processing Application

This is an image processing application developed using Python and the Tkinter framework. The app allows users to load, process, and save images with various preprocessing techniques, such as negative transformation, contrast stretching, resizing, and more. It also provides an interface for users to input their details, which are saved to a CSV file.

## Features

- **Image Preprocessing Techniques**:
  - **Negative Transformation**: Converts the image to its negative, inverting the pixel values.
  - **Contrast Stretching**: Enhances the contrast of the image by mapping input intensity values to a new range.
  - **Resize**: Allows users to resize the image to custom dimensions.
  - **Histogram**: Displays the image histogram (for both color and grayscale images).
  - **Equalized Histogram**: Performs histogram equalization to improve the contrast in the image.
  - **Log Transformation**: Applies logarithmic scaling to the pixel values, improving visibility of low-intensity areas.
  - **Gamma Transformation**: Adjusts the brightness of the image using a gamma correction technique.
  - **Grayscale Conversion**: Converts a color image to grayscale.

- **User Details Input**: Users can enter their details such as name, age, sex, height, weight, eye color, hair color, state, and charges. These details are saved to a CSV file.

- **Image Download**: Users can save the processed image to their local machine.

## Requirements

Before running the application, make sure to install the required libraries:
- **Grayscale Conversion**: Click on **"Grayscale"** to convert the image to grayscale.

Each operation modifies the image, and you can immediately see the updated image on the canvas. If needed, you can undo changes using the history stack.

### 3. Enter User Details
Below the image, enter the following details:
- **Name**
- **Age**
- **Sex**
- **Height**
- **Weight**
- **Eye Color**
- **Hair Color**
- **State**
- **Charges**

Click **"Save Details"** to save the entered information in a CSV file (`user_details.csv`).

### 4. Download Processed Image
Once you are satisfied with the changes, click on the **"Download Image"** button to save the processed image to your computer. You can save it in your preferred format (JPG or PNG).

### 5. Exit
Click **"Exit"** to close the application when you are done.

---

## Preprocessing Techniques Explained

### 1. Negative Transformation
- **Description**: The negative transformation inverts the pixel values of the image. Each pixel value is subtracted from the maximum possible value (255 for 8-bit images).
- **Use Case**: Often used in photographic effects and image analysis tasks to highlight low-intensity areas in the image.

### 2. Contrast Stretching
- **Description**: Contrast stretching enhances image contrast by mapping a set of input pixel values to a wider range of values.
- **Use Case**: Useful when the image has low contrast, and we want to stretch the pixel intensity range to improve visibility.

### 3. Resize
- **Description**: Resize the image to user-defined dimensions.
- **Use Case**: Helpful when preparing images for specific display sizes, for efficient storage, or when images need to be sent or displayed in a fixed size.

### 4. Histogram
- **Description**: A histogram represents the frequency distribution of pixel intensities in the image. It shows how many pixels have each intensity level.
- **Use Case**: Helps to analyze the overall brightness and contrast of the image. It is useful for understanding the pixel intensity distribution.

### 5. Equalized Histogram
- **Description**: Histogram equalization improves the contrast of an image by redistributing the pixel intensities so that the histogram of the image becomes uniformly distributed.
- **Use Case**: Widely used to improve the contrast of images, especially in low-light or poor-quality images.

### 6. Log Transformation
- **Description**: Applies a logarithmic scale to the pixel values. The logarithmic function is useful for enhancing details in darker areas of an image.
- **Use Case**: Used in applications like medical imaging where details in dark regions need to be enhanced.

### 7. Gamma Transformation
- **Description**: Gamma transformation adjusts the brightness of the image using a power-law function. It enhances or darkens images based on the gamma value.
- **Use Case**: Useful for adjusting image brightness for applications in photography, video processing, and medical imaging.

---

## Contributing

I welcome contributions from the community! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your forked repository.
5. Open a pull request detailing your changes.

---
