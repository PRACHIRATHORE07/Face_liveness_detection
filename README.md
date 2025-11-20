# Face_liveness_detection
AI-Powered Face Liveness Detection: This AI/ML-driven solution prevents spoofing using multimodal detection, including random dot tracing, facial movements, and audio cues. Trained on the LCC FASD and DFDC dataset, it ensures secure, accessible, and scalable authentication
# 🔒 Face Liveness Detection using Depth Map Prediction  

![Demo](https://github.com/user-attachments/assets/6af8aacc-66aa-4e36-9b1a-b94806d60b1f)

---

## 📌 About the Project  
This project is an application of **Convolutional Neural Networks (CNNs)** and **Computer Vision** to detect whether a face is **real or spoofed** in a real-time environment.  

- A video frame captured from the webcam is passed into a **pre-trained model**.  
- The model is trained on **depth maps** of images from the dataset.  
- The **depth map generation** itself is performed using a separate CNN model.  

---

## ⚙️ Setup Instructions  

### 1️⃣ Create a Virtual Environment  
```bash
python -m venv myenv
myenv\Scripts\activate   # On Windows
source myenv/bin/activate   # On Linux/Mac
```


## Steps to perform the authentication

![Screenshot 2024-11-09 084420](https://github.com/user-attachments/assets/6a02020c-f82a-4ab1-a248-d4697b86b20e)

---

## 🛠️ Steps to Perform Authentication  

### **Step 1: Start the Authentication Process**  
- **Start Button**: Click on the **Start** button to initiate the face authentication process.  

### **Step 2: Display Rules and Guidelines**  
A pop-up window will appear with the following instructions:  
- 📏 **Align Your Face**: Ensure your face is 15–20 cm from the camera.  
- 💡 **Lighting**: Stay in a well-lit environment for better capture.  
- 🖼️ **Background**: Prefer a plain background to avoid distractions.  

### **Step 3: Face Authentication Begins**  
- 🔴 **Follow the Red Dot**: A red dot will appear on the screen. Move your eyes to follow it.  
- 🗣️ **Read the Words**: A word will appear below the dot—read it aloud to assist with voice recognition.  
- 🙂 **Stay Still**: Keep your head still while only moving your eyes.  

### **Step 4: Verification and Feedback**  
- ⚡ **Processing**: The system processes the collected data.  
- ✅ **Success**: Access granted if authentication passes.  
- 🔄 **Retry**: If authentication fails, retry or follow on-screen instructions.  

---

## 💡 Tips for Effective Authentication  
- Maintain 15–20 cm distance from the camera.  
- Avoid obstructions covering your face.  
- Speak clearly when reading the displayed words.  

---

## 🛠️ Troubleshooting  
- 🎥 **Camera Issues**: Ensure your camera is functioning. Restart the device or check permissions if needed.  
- 💡 **Lighting Problems**: Adjust lighting to ensure your face is well-lit. Avoid strong backlight.  
- 🔇 **Background Noise**: Use a quiet environment for accurate voice recognition.  

---

## 🧠 The Convolutional Neural Network  

- **Architecture**:  
  - 3 Convolutional layers (with ReLU activation)  
  - 1 Fully connected layer  

- **Training Configuration**:  
  - Epochs: **10**  
  - Batch size: **32**  
  - Train/Test split: **75:25**  

---


