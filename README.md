# ML-Based-Intelligent-Data-Driven-Model-to-Secure-Intra-Vehicle-Communication-Project


Overview:  
This project focuses on enhancing the security of intra-vehicle communication systems by developing a smart, data-driven intrusion detection system (IDS) using Machine Learning (ML). Modern vehicles rely on internal networks like the Controller Area Network (CAN) for communication between electronic components, but these networks are vulnerable to cyberattacks due to the lack of built-in security mechanisms. This project addresses this critical issue by leveraging ML algorithms to monitor, analyze, and classify CAN bus traffic in real time, distinguishing between normal and malicious messages.  

Key Features:  
- Real-Time Anomaly Detection: Monitors CAN bus traffic to detect and block malicious activities, such as spoofing or injection attacks, using features like message frequency, ID patterns, and payload structures.  
- Machine Learning Models: Implements lightweight ML algorithms (e.g., Decision Trees, Random Forest, SVM, and KNN) optimized for high accuracy and low computational overhead, suitable for embedded systems like Electronic Control Units (ECUs).  
- Data-Driven Approach: Utilizes feature engineering and supervised learning to train models on real-world automotive datasets, ensuring robust threat detection.  
- User-Friendly Interface: Includes a GUI (built with Tkinter) for visualizing alerts, model performance, and detection results, aiding engineers in timely responses.  
- Scalability: Designed to integrate seamlessly with modern vehicle systems while maintaining minimal resource usage.  

Technologies Used:  
- Programming Language: Python  
- Libraries/Frameworks: Scikit-learn, Pandas, Genetic Selection  
- GUI: Tkinter  

Project Workflow:  
1. Data Preprocessing: Filters noise and normalizes raw CAN bus data.  
2. Feature Extraction: Analyzes message IDs, timing, and payloads for anomaly indicators.  
3. Model Training & Evaluation: Compares ML algorithms using metrics like accuracy, precision, and F1-score.  
4. Real-Time Detection: Blocks malicious packets and logs alerts while updating the model iteratively.  

Outcome:
The system provides a reliable, automated security layer for connected vehicles, mitigating cyber threats and enhancing driver safety. It demonstrates the potential of ML in securing IoT-enabled transportation systems, paving the way for safer, smarter automotive ecosystems.
