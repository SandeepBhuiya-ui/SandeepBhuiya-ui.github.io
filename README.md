# Sandeep Bhuiya

📍 **Minneapolis, MN**  
📧 **Email**: sandeepbhuiya.2001@gmail.com  
📞 **Phone**: (510)-377-2297  
🔗 **LinkedIn**: [Sandeep Bhuiya](https://www.linkedin.com/in/sandeep-bhuiya/)  
🔗 **GitHub**: [SandeepBhuiya-ui](https://github.com/SandeepBhuiya-ui)  

---

## Education

**University of Minnesota, Twin Cities**  
*Master of Science in Data Science*  
*GPA: 3.6 | May 2025*  

**SRM Institute of Science and Technology**  
*Bachelor of Technology in Computer Science*  
*GPA: 4.0 | May 2023*  

---

## Skills

**Programming Languages**: Java, Python, C, C++, R, SQL, Julia  
**Technologies**: Pandas, NumPy, Matplotlib, SciPy, Scikit-Learn, TensorFlow, Keras, PyTorch, Azure, PySpark, Databricks, Spark, AWS, Git, Bash, Google Cloud, BigQuery, DBT, PowerBI  
**Tools**: Jupyter Notebook, Visual Studio Code (VS Code), Anaconda, GitHub, Excel, Docker  

---

## Work Experience

### WARP, Los Angeles, California  
**Data Science Intern | May 2023 - Present**  
- Managed key data preprocessing tasks, cleansing and structuring 500,000+ data points.
- Performed advanced SQL queries for insightful freight logistics analysis.
- Boosted route optimization efficiency by 8% using time-series analysis and K-Means clustering.
- Applied NLP for efficient zip code-company matching to enhance distribution network density.
- Transformed and upgraded data dashboards in PowerBI and Tableau, increasing stakeholder engagement by 3%.

### Bit Brothers, Bengaluru, India  
**ML Research Assistant | Jan 2023 - Aug 2023**  
- Analyzed 10+ academic articles on NLP and OCR technologies, proposing context-aware recognition enhancements.
- Enhanced text extraction accuracy from images by 2% using Hugging Face's NLP models with OCR technology.
- Optimized text recognition from images, achieving a 3% increase in processing speed for 10,000+ samples.

### Ikshan, Bengaluru, India  
**Data Science Intern | Nov 2022 - Jan 2023**  
- Enhanced image object detection models via Stochastic Gradient Descent (SGD) optimization, increasing detection speed by 10%.
- Improved the YOLO algorithm, leading to a 4% precision boost and a 5% speed increase.
- Enhanced CNN algorithm for contour box detection, increasing efficiency by 6%.

---

## Projects

### [Aerial Semantic Segmentation](https://github.com/SandeepBhuiya-ui/Semantic-Segmentation-for-Aerial-Data)
![Aerial Semantic Segmentation](https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png)
Semantic segmentation for aerial data is a computer vision task that involves dividing an aerial image into meaningful and distinct regions, each corresponding to a specific object or land cover class. Unlike simple object detection, semantic segmentation assigns a class label to every pixel in the image, providing a detailed understanding of the scene.

#### Objective
The primary goal is to classify each pixel in an aerial image into predefined classes such as roads, buildings, vegetation, water bodies, and other relevant land cover categories.

#### Challenges
- Varying lighting conditions, shadows, occlusions, and different scales of objects.
- Handling these challenges requires robust algorithms capable of capturing contextual information and spatial relationships.

#### Applications
- **Urban Planning**: Analyzing land use patterns, identifying infrastructure, and monitoring urban development.
- **Precision Agriculture**: Identifying crop types and health to optimize resource allocation and improve yield.
- **Environmental Monitoring**: Monitoring changes in natural landscapes.
- **Disaster Response**: Assessing damage after natural disasters by identifying affected areas and infrastructure.

#### Techniques
- **Convolutional Neural Networks (CNNs)**: Models like U-Net, SegNet, and DeepLab adapted for aerial imagery.
- **Transfer Learning**: Fine-tuning pre-trained models on large datasets for aerial data.
- **Spatial Context Modeling**: Techniques like dilated convolutions and atrous spatial pyramid pooling for large receptive fields.

---

### [Distracted Driver Detection](https://github.com/SandeepBhuiya-ui/Distracted-Driver-Detection)
![Distracted Driver Detection](https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png)
Driving a car is a difficult undertaking that needs your full focus. Any action that diverts the driver's attention from the road constitutes distracted driving. Numerous studies have distinguished between three basic categories of distraction: visual (driver's eyes off the road), manual (driver's hands off the wheel), and cognitive (driver's head off the task of driving).

#### Data
- **Dataset**: StateFarm dataset containing snapshots from a video captured by a camera mounted in the car.
- **Training Set**: ~22.4K labeled samples with equal distribution among the classes and 79.7K unlabeled test samples.
- **Classes**: 
  - c0: safe driving
  - c1: texting - right
  - c2: talking on the phone - right
  - c3: texting - left
  - c4: talking on the phone - left
  - c5: operating the radio
  - c6: drinking
  - c7: reaching behind
  - c8: hair and makeup
  - c9: talking to passenger

#### Assessment Metric
- **Log Loss**: Measures the degree of certainty with which we label a driver's behaviour as distracted, crucial for model effectiveness.

#### Adaptive Learning
- **Transfer Learning**: Reusing model weights from pre-trained models on well-known computer vision benchmark datasets.
- **Technology Used**: 
  - **Python Libraries**: OpenCV, TensorFlow, Scikit-Learn, Pandas
  - **Computer Vision Techniques**: CNN, Data Augmentation, Transfer Learning

#### CNN Model Architecture
- **Layers**:
  - 3 Convolutional layers (with ReLU, MaxPooling, and Dropout)
  - A flatten layer
  - 2 Dense layers with ReLU and Dropouts
  - 1 Dense layer with softmax for classification

---

Feel free to explore my repositories for more details on these projects and my contributions.
