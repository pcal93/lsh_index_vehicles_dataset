
---

# 🚗 **Vehicle Recognition Project**

**Course**: Multimedia Information and Computer Vision
**Authors**: Alberto Caruso, Yuli Orozco, Pietro Calabrese

## ✨ **Project Overview**

The **Vehicle Recognition Project** is a cutting-edge system designed for **vehicle classification** and **image retrieval** based on deep learning. By leveraging pre-trained convolutional neural networks such as **VGG16** and **VGG19**, the project showcases the power of **deep feature extraction** for understanding vehicle images. Through innovative techniques like **Feature Reuse** and **Fine-Tuning**, our system adapts these models to a specialized vehicle dataset, achieving outstanding performance in classifying and retrieving vehicle-related images.

The project not only provides a **high-performance classifier** but also integrates an **image search engine** to allow users to find similar vehicles from a large dataset, making it an essential tool for applications such as **autonomous driving** and **vehicle database management**.

### 🏆 **Key Features**

* **🔍 Feature Extraction**:

  * Utilizing pre-trained **VGG16** and **VGG19** networks, our system extracts **high-level features** from vehicle images, creating a deep representation that facilitates accurate vehicle classification and comparison.

* **🛠️ Fine-Tuning**:

  * By replacing the last layer of the VGG models, we adapt the networks to the unique characteristics of the vehicle dataset, enhancing model performance on specific vehicle types.

* **⚡ Fast Similarity Search**:

  * Implementing **Locality Sensitive Hashing (LSH)** enables fast and efficient similarity search on high-dimensional feature vectors, allowing rapid retrieval of similar images.

* **🌐 Web-Based Interface**:

  * A user-friendly **web interface** lets users easily interact with the system, uploading vehicle images and searching for similar ones from a large database.

---

### 📚 **Datasets Used**

* **Flickr Dataset**:

  * The **Flickr dataset** consists of a large collection of vehicle images, sourced from **Flickr**. These images represent various vehicle types and are used to train and evaluate the vehicle recognition model. The diversity in image styles, environments, and vehicle types provides a rich source of data for deep learning applications.

* **Vehicles Dataset (10 Classes)**:

  * This dataset contains **vehicle images** categorized into **10 distinct classes of cars**, offering a diverse set of vehicle types for classification tasks. These 10 classes serve as the foundation for the vehicle recognition and retrieval system. The dataset includes various angles, lighting conditions, and vehicle models, allowing the model to generalize effectively across real-world scenarios.

---

### 🎯 **Project Objectives**

The project has four primary goals:

1. **🔹 Vehicle Classification**:

   * Leverage deep learning to classify vehicles accurately from images using state-of-the-art models like **VGG16** and **VGG19**.

2. **🔹 Image Retrieval**:

   * Develop an **image search engine** that allows users to retrieve similar vehicle images based on deep feature vectors, making it ideal for large-scale vehicle databases.

3. **🔹 User Interface**:

   * Build an interactive **web interface** for users to easily upload and search vehicle images with real-time results.

4. **🔹 Performance Evaluation**:

   * Measure the **retrieval performance** of the system using precision, recall, **Mean Average Precision (mAP)**, and other relevant metrics to evaluate the effectiveness of the image search engine.

---

### 🧠 **Techniques Used**

* **🧩 VGG16 and VGG19 Models**:

  * **VGG16** and **VGG19**, two powerful deep convolutional networks, are used to extract deep, semantically rich features from images. These pre-trained models provide a strong starting point for vehicle classification tasks.

* **🔄 Feature Reuse**:

  * **Feature Reuse** involves utilizing the extracted deep features from the pre-trained networks to train an external classifier. This allows us to create a more efficient vehicle recognition system.

* **🎯 Fine-Tuning**:

  * The **fine-tuning** technique is applied by replacing the final layer of the VGG models and retraining them on our vehicle dataset. This ensures the model adapts to the specific features and nuances of vehicle images.
