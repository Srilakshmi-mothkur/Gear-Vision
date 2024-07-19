# Gear Vision

**Gear Vision** is a deep learning-based model designed for detecting and classifying car parts from images. This project includes data preprocessing, augmentation, model training, and real-time predictions.

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

The model performs well, handling noisy images and providing accurate predictions for real-time images, making it suitable for applications where customers submit live images of car parts.

## Future Improvements

1. **Real-Time API:** Develop an API for real-time image classification and inventory checks.
2. **User Interface:** Create a web or mobile app for customers to upload images and get instant results.
3. **Enhanced Processing:** Implement techniques to handle various image qualities and lighting conditions.
4. **RAG Application:** Build a RAG system to provide contextual information and FAQs alongside image classification.

These improvements will enhance customer interaction and streamline part identification and support.

## License

This project is licensed under the MIT License.

