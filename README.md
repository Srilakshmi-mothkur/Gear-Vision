# Gear Vision

**Gear Vision** is a deep learning model for detecting and classifying various car parts, designed to assist firms in automating and optimizing parts identification and inventory management.

## Technologies Used

- **Deep Learning Framework:**
  - **TensorFlow/Keras**: Used for building and training the deep learning model with MobileNetV2 architecture.
- **Image Processing:**
  - **OpenCV**: Applied for various image processing tasks.
  - **PIL (Pillow)**: Utilized for loading and resizing images.
- **Data Augmentation:**
  - **ImageDataGenerator**: Employed for augmenting the dataset with transformations such as rotation, shifting, shearing, and flipping.
- **Programming Language:**
  - **Python**: The primary language for data processing, model training, and evaluation.
- **Additional Libraries:**
  - **NumPy** and **Pandas**: Used for data manipulation.
  - **Matplotlib**: For visualizing learning curves and predictions.

## Results

The model was tested with noisy images and it provides accurate predictions for real-time images, making it suitable for applications where customers submit live images of car parts.
| ![Image 1](https://github.com/user-attachments/assets/c40577e6-8cc9-4b0e-980f-8a517003d63f) | ![Image 2](https://github.com/user-attachments/assets/123e7684-c657-41a0-99b8-0b8746221b8d) |
|:--:|:--:|
| **Radiator Hose** | **Brake Rotor** |

| ![Image 3](https://github.com/user-attachments/assets/76153ff8-9b5b-4151-9f9e-5a5aef6baa5e) | ![Image 4](https://github.com/user-attachments/assets/fdab70ad-34e6-4b61-8e21-7318a69e17a2) |
|:--:|:--:|
| **Engine Block** | **Water Pump** |







## Future Improvements

1. **User Interface:** Create a web app for customers to upload images and get instant results.
2. **Enhanced Processing:** Implement techniques to handle various image qualities and lighting conditions.
3. **RAG Application:** Build a RAG system to provide contextual information and FAQs alongside image classification.

These improvements will enhance customer interaction and streamline part identification and support.

## License

This project is licensed under the MIT License.

