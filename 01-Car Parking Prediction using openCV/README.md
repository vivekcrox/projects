# 🚧🚓 Car Parking Prediction using OpenCV Python | Computer Vision 🚓🚧
##  ❄ Part-1: Parking Space Finder Script                  
📁 **(File : parkingSpacePicker.py):**

🌠 **Objective:**
   - Designed for creating a parking space finder using basic image processing techniques.

🌠 **Program Structure:**
   - Split into two parts: a "picker" for manual space selection and main code for processing and displaying results.

🌠 **Picker Part:**
   - Opens a parking lot image for manual selection.
   - Left-click adds rectangles for selected spaces; right-click removes.
   - Utilizes OpenCV for image processing and Pickle for storage.
   - Continuously displays image, updates rectangles, and saves positions in "CarParkPos" file.

⚙ **Summary:**
   - Offers a simple and effective method for creating a parking space finder.

## ❄ Part-2 : Parking Space Occupancy Detection Code
           
📁 **(File: main.py) :**

🌠 **Objective:**
   - Designed for monitoring parking space occupancy using a video feed.

🌠 **Initialization:**
   - Loads previously marked positions from "CarParkPos" file.
   - Displays rectangles on-screen representing marked spaces.

🌠 **Video Processing Loop:**
   - Captures and processes frames from "carpark.mp4" continuously.
   - Crops frames based on loaded positions for each parking space.

🌠 **Image Processing Steps:**
   - Grayscale conversion, Gaussian blur, adaptive thresholding, median blur, and dilation.
   - Enhances features for effective car detection within each space.

🌠 **Occupancy Determination:**
   - Counts non-zero pixels in processed images.
   - Displays counts on rectangles (green for available, red for occupied).
   - Total available spaces count is shown.

🌠 **Dynamic Adjustments:**
   - Changes color and thickness of rectangles based on observed counts.
   - Video feed continuously loops for ongoing testing.

🌠 **Accuracy Considerations:**
   - Depends on factors like video quality, camera stability, and image processing effectiveness.
   - Requires parameter fine-tuning for optimal results.
#
🏷 **Conclusion:**
   
   🛠📕 Provides a visual representation of parking space occupancy.
   
   🛠📕 Valuable tool for monitoring and managing parking lots.
