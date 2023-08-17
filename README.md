# People Counting System for Metro Bogeys

**Overview:**
The People Counting System for Metro Bogeys is an intelligent solution designed to provide real-time crowd estimation in metro train carriages to assist commuters in making informed decisions about their travel. The system utilizes computer vision and deep learning techniques, specifically Ultralytics YOLOv8 (You Only Look Once), to detect and count the number of people present in each metro bogey. LED lights positioned at the entry points of the train carriages will change color to indicate whether the bogey is crowded (red light) or uncrowded (green light), allowing passengers to make better-informed choices and optimize their travel experience.

**Key Features:**
1. Real-time People Counting: The system performs real-time object detection using Ultralytics YOLOv8 to accurately count the number of people present in each metro bogey as the train arrives at the platform.

2. LED Light Indicators: LED lights at the entrance of each bogey change color based on the number of people detected. A red light indicates a crowded bogey, while a green light signifies an uncrowded bogey.

3. Enhanced Commuter Experience: By providing real-time crowd information, the system empowers commuters to choose the best-suited bogey for their travel, leading to a more comfortable and efficient journey.

4. Customizable Configuration: The system's parameters, such as the detection threshold for crowd determination, can be adjusted based on specific metro systems and commuter preferences.

5. Edge Computing: The model is optimized for edge devices, ensuring fast and efficient inference even in resource-constrained environments like metro stations.

**Project Implementation:**
1. Data Collection: Gather a diverse dataset of labeled images, capturing various crowd densities in metro bogeys.

2. Data Preparation: Annotate the images to define bounding boxes around people, and convert the annotations to YOLO format.

3. Model Configuration: Fine-tune the Ultralytics YOLOv8 architecture to detect people in metro bogey images.

4. Training: Train the YOLO model on the annotated dataset, optimizing it to accurately count people in different bogey scenarios.

5. Model Evaluation: Evaluate the model's performance on a validation dataset to ensure its accuracy and generalization.

6. LED Control: Integrate the model with LED control mechanisms to change light colors based on people count.

7. Deployment: Deploy the trained model on edge devices capable of real-time inference at metro stations.

**Ethical Considerations:**
1. Privacy: Implement measures to protect the privacy of commuters and ensure compliance with data protection regulations.

2. Transparency: Provide clear signage or information regarding the purpose and operation of the People Counting System to commuters.

3. Data Security: Safeguard all collected and processed data to prevent unauthorized access or misuse.

**Benefits:**
- Improved Commuter Experience: Passengers can choose less crowded bogeys, enhancing their comfort during travel.
- Optimal Utilization: Evenly distribute passenger loads among bogeys, optimizing train capacity utilization.
- Data-Driven Decisions: Metro authorities can gather insights on passenger demand and optimize train scheduling.

**Conclusion:**
The People Counting System for Metro Bogeys is an innovative project that leverages computer vision and deep learning to provide real-time crowd estimation. By integrating this system with LED light indicators, it offers commuters a seamless way to identify crowded or uncrowded bogeys and optimize their travel experience within the metro system. The project demonstrates the potential of AI-based solutions in enhancing public transportation services and ensuring passenger convenience and satisfaction.
