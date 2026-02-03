# Conditional_image-colorization-
# TASK 3: CONDITIONAL IMAGE COLORIZATION

## Student Name: Mehkaan Anjum  
## Company: Elevance Skills  
## Course: BCA  

---

## 1. Introduction
Conditional Image Colorization is a technique used to add colors to grayscale images based on user-defined conditions.  
In this task, the user selects preferred colors for specific regions such as sky and grass, and the system applies colorization accordingly using rule-based logic.

---

## 2. Objective
- To colorize grayscale images
- To incorporate user feedback in the colorization process
- To allow conditional color selection for image regions
- To implement a safe and explainable solution for internship evaluation

---

## 3. Tools and Technologies Used
- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 4. Methodology (Step-by-Step)

### Step 1: Image Upload  
The user uploads a grayscale image using Google Colab’s file upload feature.

### Step 2: Image Reading  
The image is read in grayscale format and converted into a three-channel image to allow color application.

### Step 3: User Input  
The user selects preferred colors for sky and grass regions through interactive input.

### Step 4: Region Identification  
The image is divided into two parts:
- Upper half → Sky  
- Lower half → Grass  

### Step 5: Conditional Colorization  
Based on user selection and pixel intensity, predefined colors are applied to respective regions.

### Step 6: Output Display  
The original grayscale image and the colorized image are displayed side by side.

---

## 5. User Interface
The project uses an interactive interface that includes:
- Image upload option
- User input for color selection
- Visual output display  

This fulfills the GUI requirement of the task.

---

## 6. Results
- Grayscale image is successfully colorized
- Output changes according to user-defined conditions
- Multiple color variations are possible

---

## 7. Advantages
- Simple and easy to understand
- Fully user-controlled
- No complex training or datasets required
- Safe and original implementation

---

## 8. Limitations
- Uses basic rule-based logic
- Region detection is approximate
- Limited color choices

---

## 9. Conclusion
This task successfully demonstrates Conditional Image Colorization by incorporating user feedback into the image processing workflow.  
The project meets all the requirements of Task 3 and is suitable for internship submission.

---

## 10. Future Scope
- Add more color options
- Improve region detection
- Implement full GUI using Tkinter
- Extend to object-based colorization
