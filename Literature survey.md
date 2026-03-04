# Literature Survey

---

## Paper 1: Deep Learning Methods for Poultry Disease Prediction Using Images

**Source:** Computers and Electronics in Agriculture, Volume 230 (2025), Article 109765  
**DOI:** https://doi.org/10.1016/j.compag.2024.109765  
**File Reference:** Deep_learning_methods_for_poultry_diseas.pdf  

### Objective
Evaluate the generalizability of deep learning models for poultry disease prediction using fecal images across Tanzania and Malawi. Compare binary and multiclass classifiers.

### Methodology
- Dataset 1: Tanzania (Healthy, Newcastle Disease, Salmonella, Coccidiosis)
- Dataset 2: Malawi (Healthy, Newcastle Disease)
- Data augmentation using Keras ImageDataGenerator
- Transfer Learning Models:
  - MobileNetV2
  - DenseNet121
  - ResNet152
- 6 Models Developed:
  - 3 Binary classifiers
  - 3 Multiclass classifiers
- Evaluation Metrics: Accuracy, F1-score, Confusion Matrix, Error Rate

### Key Features
- Cross-country evaluation
- Binary vs Multiclass comparison
- Transfer learning implementation
- Class imbalance handling
- Performance visualization

### Results Summary
- Tanzania: >90% accuracy (Best: 98%)
- Malawi: Binary models ~80–82%, Multiclass dropped significantly
- Binary models showed better generalization

### Limitations
- Breed and environmental differences
- Dataset imbalance
- Limited Malawi disease categories
- Difficult rural data collection

### Relevance to Project
**VERY HIGH** – Strong foundation for image-based poultry disease detection and cross-region generalization.

---

## Paper 2: Automatic Detection of Poultry Diseases from Fecal Images Using Deep Learning

**Source:** Frontiers in Artificial Intelligence, Volume 4 (2021), Article 733345  
**DOI:** https://doi.org/10.3389/frai.2021.733345  
**File Reference:** frai-05-733345.pdf  

### Objective
Develop automated poultry disease detection using deep learning for early diagnosis.

### Methodology
- 4 Classes: Healthy, Newcastle, Salmonella, Coccidiosis
- Image preprocessing & augmentation
- Transfer Learning Models:
  - VGG16
  - ResNet50
  - InceptionV3
- Softmax activation
- Metrics: Accuracy, Precision, Recall, F1-score

### Results
- ResNet50 achieved highest accuracy (>90%)
- Good differentiation between similar fecal patterns

### Limitations
- Small dataset
- Controlled environment images
- No cross-region validation

### Relevance
**VERY HIGH** – Core CNN-based poultry disease classification reference.

---

## Paper 3: IoT Based Smart Monitoring System for Efficient Poultry Farming

**Source:** Webology, Volume 19, Number 1 (2022)  
**DOI:** https://doi.org/10.14704/WEB/V19I1/WEB19270  
**File Reference:** IoT_Based_Smart_Monitoring_System_for_Ef.pdf  

### Objective
Design low-cost IoT system to monitor poultry house environment.

### Methodology
- ESP32 Microcontroller
- DHT11 Sensor (Temperature & Humidity)
- MQ135 Gas Sensor
- PIR Motion Sensor
- Blynk IoT App
- Embedded C++

### Features
- Real-time monitoring
- Remote mobile access
- Intruder detection
- Remote temperature control
- Low-cost implementation

### Limitations
- Manual ventilation
- Small-scale testing
- No AI prediction
- Internet dependency

### Relevance
**VERY HIGH** – Useful for integrating IoT with AI disease detection.

---

## Paper 4: New Technologies for Monitoring Bird Migration and Behaviour

**Source:** Animal Biotelemetry (2022)  
**File Reference:** New technologies for monitoring bird migration and behaviour.pdf  

### Objective
Review modern tracking technologies for bird migration and behavior.

### Technologies Reviewed
- GPS Tracking
- Satellite Telemetry
- RFID
- Accelerometers
- Geolocators
- Automated Telemetry Systems

### Key Insights
- High-resolution migration mapping
- Behavior detection using motion sensors
- Sensor miniaturization advancements

### Limitations
- High cost
- Battery constraints
- Ethical concerns
- Large data management issues

### Relevance
**MEDIUM–HIGH** – Useful for behavioral and sensor-based monitoring systems.

---

## Paper 5: Evaluation of ProMED-mail as an Electronic Early Warning System

**Source:** Journal of the American Veterinary Medical Association (2006)  
**File Reference:** Evaluation_of_ProMED_mail_as_an_electron.pdf  

### Objective
Evaluate ProMED-mail as early warning system for emerging animal diseases.

### Methodology
- 10,490 reports analyzed (1996–2004)
- Geographic distribution analysis
- Disease type classification
- Comparison with OIE reports

### Key Findings
- Covered 191 countries
- >50% viral diseases
- Low correction rate (2%)

### Limitations
- Reporting bias
- Uneven global representation
- Not full surveillance system

### Relevance
**HIGH** – Supports digital disease surveillance integration.

---

## Paper 6: Applications of Precision Livestock Farming Tools in Poultry Production

**Source:** Frontiers in Veterinary Science, Volume 5 (2018), Article 263  
**DOI:** https://doi.org/10.3389/fvets.2018.00263  
**File Reference:** fvets-05-00263.pdf  

### Objective
Review precision livestock farming technologies in poultry.

### Technologies
- Acoustic sensors
- Machine vision systems
- Environmental sensors
- Weight & feed monitoring

### Key Findings
- Early disease detection using sound
- Automated behavior monitoring
- Reduced labor & improved productivity

### Limitations
- High setup cost
- Technical complexity
- Data storage challenges

### Relevance
**VERY HIGH** – Strong framework for AI + IoT integrated poultry health system.

---
| S.No | Study Area                                                          | Techniques / Methods Used                                                                                                                            | Key Findings                                                                                                   | Limitations                                                                           | Relevance to Proposed System                                                                                                  |
| ---- | ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| 1    | Poultry Disease Prediction using Deep Learning (Cross-Region Study) | Transfer Learning (MobileNetV2, DenseNet121, ResNet152), Binary & Multiclass CNN models, Data Augmentation, Cross-region testing (Tanzania & Malawi) | Binary classifiers achieved up to 98% accuracy; better cross-region generalization than multiclass models      | Performance drop across regions; dataset imbalance; limited disease classes in Malawi | Very High – Provides strong CNN architecture foundation and generalization insights for disease detection system              |
| 2    | Automatic Poultry Disease Detection from Fecal Images               | Transfer Learning (VGG16, ResNet50, InceptionV3), Image preprocessing, Data augmentation, Softmax classification                                     | ResNet50 achieved >90% accuracy; effective classification of visually similar diseases                         | Limited dataset size; controlled environment images; no cross-country validation      | Very High – Core reference for image-based poultry disease classification module                                              |
| 3    | IoT-Based Smart Poultry Farm Monitoring                             | ESP32, DHT11, MQ135, PIR sensor, Blynk IoT platform, Embedded C++                                                                                    | Real-time monitoring of temperature, humidity, gas levels; remote mobile access; functional low-cost prototype | Manual ventilation; small-scale testing; no AI prediction; internet dependency        | Very High – Supports environmental monitoring module integration with AI-based disease detection                              |
| 4    | Bird Migration & Behavior Monitoring Technologies                   | GPS tracking, Satellite telemetry, RFID, Accelerometers, Automated radio telemetry systems                                                           | High-resolution tracking; behavior detection using motion sensors; improved miniaturization                    | High cost; battery limitations; data management challenges                            | Medium–High – Useful for behavioral monitoring and sensor-based poultry tracking expansion                                    |
| 5    | Electronic Early Warning System for Animal Diseases (ProMED-mail)   | Digital disease reporting analysis, Retrospective outbreak study, Geographic distribution analysis                                                   | Global coverage (191 countries); early outbreak reporting; low correction rate                                 | Reporting bias; uneven geographic representation; not full surveillance system        | High – Supports integration of digital surveillance and outbreak alert system                                                 |
| 6    | Precision Livestock Farming in Poultry Production                   | Acoustic sensors, Machine vision, Environmental sensors, Automated data analytics                                                                    | Early disease detection via sound analysis; automated behavior monitoring; improved productivity               | High installation cost; technical complexity; data storage challenges                 | Very High – Provides framework for combining AI, IoT, vision, and sound-based monitoring into integrated smart poultry system |
