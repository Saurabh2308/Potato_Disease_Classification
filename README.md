# Potato_Disease_Classification

This deep learning project aims to address the agricultural challenges faced by farmers, specifically in the cultivation of potatoes. Farmers often experience economic losses and crop waste due to various diseases affecting potato plants. To mitigate these issues, we have implemented an image classification solution using Convolutional Neural Networks (CNN).

### Project Description:
The project focuses on creating a robust model capable of classifying diseases in potato plants based on images. Leveraging TensorFlow, we utilize a Convolutional Neural Network to effectively learn and distinguish between healthy and diseased potato plants.

The dataset is organized using tf.data.Dataset, providing efficient data handling and training capabilities. Data augmentation techniques are applied to enhance the model's ability to generalize and recognize patterns effectively.

For deployment and integration into real-world scenarios, TensorFlow Serving and FastAPI are employed to create a robust backend server. This allows for seamless model deployment and inference serving.

To optimize the model's efficiency, techniques such as quantization and TensorFlow Lite are implemented. These optimizations ensure that the model can be deployed on edge devices and integrated into applications with resource constraints.

The frontend is built using React JS, providing an intuitive and user-friendly interface. Users, specifically farmers, can interact with the system by uploading images of potato plants. The system then provides real-time predictions, indicating whether the plant is healthy or affected by a particular disease.

This Potato Disease Classification project represents a comprehensive solution that combines cutting-edge deep learning techniques with practical deployment strategies. It aims to empower farmers with a tool to identify and address diseases in potato plants, ultimately reducing economic losses and promoting sustainable agriculture practices.

### Technology Stack:

Model Building: TensorFlow, CNN, Data Augmentation, tf.data.Dataset
Backend Server and ML Ops: TensorFlow Serving, FastAPI
Model Optimization: Quantization, TensorFlow Lite
Frontend: React JS

### Data Preparation:
The dataset, sourced from "PlantVillage," is preprocessed using TensorFlow's image_dataset_from_directory. The images are resized to 256x256 pixels and organized into batches for efficient training.

### Data Augmentation and Partitioning:
To enhance model robustness, data augmentation techniques such as random flipping and rotation are applied. The dataset is then partitioned into training, validation, and test sets using a specified split ratio.

### Model Architecture:
The CNN model architecture consists of several convolutional and pooling layers, effectively capturing hierarchical features in the images. The model is compiled with the Adam optimizer and Sparse Categorical Crossentropy loss function for multi-class classification.

### Training and Evaluation:
The model is trained on the training set with data augmentation, and its performance is evaluated on the validation set. The training history is visualized with plots depicting training and validation accuracy and loss over epochs.

### Optimizations:
To ensure efficiency and deployment on resource-constrained devices, the model undergoes optimizations such as quantization and TensorFlow Lite conversion.

### Results and Visualization:
The trained model achieves competitive accuracy on the test set. Visualizations include plots showcasing the training and validation accuracy and loss trends. Additionally, individual predictions on a sample from the test set are displayed, providing insights into the model's performance.

### Deployment:
The model is saved for future use, and the project includes a detailed Jupyter notebook documenting the entire process. Furthermore, the project envisions a practical deployment scenario where farmers can use a website built with React JS to upload images of potato plants for real-time disease classification.

This Potato Disease Classification project aims to empower farmers with a reliable tool for identifying and managing diseases in potato crops, contributing to sustainable agriculture practices and reducing economic losses. The combination of advanced deep learning techniques and practical deployment strategies makes it a valuable asset in the field of precision agriculture






