<img width="1136" height="574" alt="nairolab-github-banner-cropped" src="https://github.com/NAIROlab-ke/Strathmore-School-ML-AI-Club_Term-2_2026/blob/main/nairolab-github-banner-cropped.png" />

# Junior Student Group (YOLO)

### 1. AI Ecosystem, Part 1 (May 7 - 14)
- **Colab and Linux CLI, Introduction** [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MbQ_D4J1lOiqfEmNwLnFpiD-gqmnXmk3)
- **Face Detection with YOLO on Colab** [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZFKzxWIkEe3ptxmgcRDKUSZeGNW1KVMN#scrollTo=148eRPF04odg)
- Training Dataset
  - [v2.v2i.yolov8-face-detection-data.zip](https://www.dropbox.com/scl/fi/f1hvkvjk1fe3qx5ze84gv/v2.v2i.yolov8-face-detection-data.zip?rlkey=msa8tjdedg2bpe34a272lzdrw&st=rr7ygsbp&dl=0)
    
    **NOTE:** This is a random dataset obtained from the [Roboflow Universe](https://universe.roboflow.com/). It hasn't been inspected for correctness or appropriateness. Feel free to use any other dataset of your choice.
    
- Test Data
  - [face-1-480p.mp4](https://www.dropbox.com/scl/fi/b1qfc1drqeut3hcq7h9ad/face-1-480p.mp4?rlkey=krg9y3fqxjzf8rwxjot1b1akc&st=if1ky3xe&dl=0)
  - [faces-image.jpeg](https://www.dropbox.com/scl/fi/4kmw6ta04pv43lk59at78/faces-image.jpeg?rlkey=vx6jozeggjmetpl8dexnia7yx&st=fzvuwnhg&dl=0)

### 2. AI Ecosystem,  Part 2 (May 21/28)
- [**Roboflow + Google Drive + Google Colab Training Pipleline Tutorial**](https://drive.google.com/file/d/1NpfRzsEuaKeDfPifsteSMr2nJxvCEU50/view?usp=drive_link)
- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZFKzxWIkEe3ptxmgcRDKUSZeGNW1KVMN#scrollTo=148eRPF04odg)
- Homework:
  - Explore and select a different dataset for the detection of an object of choice (e.g. soda-can, road or traffic signs, sunflowers, etc) from the Roboflow Universe and train a custom Ultralytics YOLO model in Colab

<!--
### 3. Realworld Football Analysis, Part 1  (May 28)
- Understanding project requirements
  - Custom data annotation of players, refs, linesmen, etc
  - Image resolution
  - Model size (parameter count)
- Homework: Basic team player detection using FIFA data
-->

### 3. Soda-Can Detection (June 4th)
- Understand Image Annotation for object detection tasks using Roboflow Platform
- Build Soda-can detection model on Google Colab
- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ywn4LSUa_OqYuXnMtqHCg5Ub_w7NcRDq?usp=drive_link)

### 4. Football Player Detection, (June 18)
- Introduce the concept of **fine-tuning** a **pre-trained** model
  - Ultralyitics YOLO is a pre-trained model that can detect upto 80 classes out-of-the-box -- including "person" (i.e human) and field sports balls (football, volleyball, basketball, etc)
  - Fine-tuning allows the pre-trained model to be used to detect classes that it was not originally trained for -- and even enhancing performance of trained classes  
- Objective is to fine-tune a YOLO model
  - distinguish between football players, goalkeepers, and refeeres (i.e. 3 new classes from the otherwise same "person" class)
  - improve football detection
- Inference results
  - Fine-tuned model should detect only 4 classes: player, referee, goalkeeper, ball
  - Other humans previously detected by pre-trained model (i.e. "person" class) should be ignored
- Lab
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QXV9V6PGTMjLT1cSG44Xlw0b9atwr_7E?usp=drive_link)
  - Upload [Football Test video](https://drive.google.com/file/d/11_AxeVf8nqumbQ2fQBYeY9Yw5unqveY3/view?usp=drive_link) to your Google Drive (i.e. `MyDrive`)
  
<!--
### 4. Traffic Light Detection, Part 1 (June 18)
- Data Collection and Image Annotation
- Homework: Build of custom YOLO model
-->
<!--
### 6. Traffic Light Detection, Part 2 (June 18)
- Deployment and testing of student models on autopilot system
-->

### 5. Understanding AI Model Training and Performance (July 2nd)

* **Dataset quality** — Accurate labels, representative samples, balanced classes, and sufficient diversity.
* **Dataset size** — More high-quality data generally leads to better generalization.
* **Data preprocessing & augmentation** — Resizing, normalization, flips, crops, color jitter, noise, etc., improve robustness.
* **Model architecture** — The choice of neural network (e.g., CNN, YOLO, U-Net, RT-DETR, ViT) determines the model's capacity and computational requirements.
* **Hyperparameters** — Learning rate, batch size, epochs, optimizer, weight decay, image resolution, and other training settings strongly influence convergence.
* **Transfer Learning**/**Fine-tuning** — Starting from pretrained weights typically reduces training time and improves performance, especially with limited data.
* **Compute resources** — GPU memory and processing power affect feasible model size, batch size, image resolution, and training time.
* **Evaluation methodology** — Appropriate metrics (e.g., Precision, Recall, F1, mAP, IoU, accuracy) and a well-designed validation/test split are essential for measuring real-world performance.
* **Deployment requirements** — Models are often optimized differently depending on whether they run in the cloud, on PCs, or on edge devices where latency, memory, and power consumption matter.

- Lab / Assignment
  - Use this [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lCBm-YgMkxE51f8howMyd0imUFjhogBV#scrollTo=QfEvrBeMHVI2) notebook to train a model for an arbitrary object detection task
  - By default, it uses [**this**](https://drive.google.com/file/d/1nXXcZtbm0oRcKmTu5oxywNjAWOYqSSef/view?usp=sharing) dataset. Upload to your Google Drive (directly under `MyDrive`).
      
### 6. Exhibition Day Capstone Project Brainstorming (July 9)
- Project Ideas
  - AI Vision-based Realtime Analysis of Strathmore School Field Sports
  - Autopilot traffic-light and road-sign recognition (DonkeyCar Platform)

### 7. Exhibition Day Rehearsals (July 16)
### 8. Exhibition Day (July 23)

<br><br>

# Senior Student Group (MediaPipe)

### 1. Introduction to Python (May 7th/14th)
- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xjif0l1T265o3CJGt48gxgq462lQq1ng?usp=sharing)
### 2. Internet of Things (IoT) Protocols with Python (May 21st)
- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OeXjPPn027Rxyq0Wdg72c1fCaw8uuCR9)
### 3. Streamlit (June 4th)
- [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wVZIgjYCBR95nNL-ynEgySJZR4MN96mN#scrollTo=kOSTeKHPsDNJ)
### 4. MediaPipe API (June 18th)
- Object Detection
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RBEKU4mP8_T52Q8IDljfTPWMY9IjCbqF?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1n0w5rwSewhPGay13mRt3GItH4coWWybD/view?usp=sharing)
- Face Detection
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HUIvbgDdP1Pm5kB16Zqhu1JXtuGG_2R9?usp=drive_link)
  - [Test Video 0](https://drive.google.com/file/d/1sPKL8GDBxEc017sYRgIHjuSquqgcdq5E/view?usp=sharing)
  - [Test Video 1](https://drive.google.com/file/d/19lJL-3Tesa9liDVnTQtPHZCERvRvsyaf/view?usp=sharing)
  - [Test Video 2](https://drive.google.com/file/d/1VIxy4oOr9bEA8-0rrIs0eCCCVDdSLjiu/view?usp=sharing)
  - [Test Video 3](https://drive.google.com/file/d/1EKW8PCeh33p2FeeKErnwUQVsV4T7vYoA/view?usp=sharing)
- Face Landmark Detection
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_5AgOQooE9SZJF5SIsVmPnatNQbugmCY?usp=drive_link)
  - [Test Video 0](https://drive.google.com/file/d/19lJL-3Tesa9liDVnTQtPHZCERvRvsyaf/view?usp=sharing)
  - [Test Video 1](https://drive.google.com/file/d/1VIxy4oOr9bEA8-0rrIs0eCCCVDdSLjiu/view?usp=sharing)
- Hand Landmark Detection
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Bn63vY6i3cBeE94bUDptUu4DbiKwQGNM?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1WmNtTK48xNdWgn4e9YWFqnuotQiW5O8X/view?usp=sharing)     
- Gesture Recognition
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AqW_c0ofphjoLQzyHyCQdOjWWbVwY8p2?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1WmNtTK48xNdWgn4e9YWFqnuotQiW5O8X/view?usp=sharing)
- Pose Landmark Detection
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PiNBxNATMRdzbg21hVHZNPYgfOknVUNE?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1P_qjE2pHV_mFSn3zfSSkdt-9sHTMNngA/view?usp=sharing)

### 5. Artificial Intelligence of Things, AIoT (July 2nd)

- **AIoT** combines **Artificial Intelligence (AI)** with the **Internet of Things (IoT)** to create smart systems that can **sense, understand, communicate,** and **respond** to their environment.
- In this lesson:
  - **MediaPipe** acts as the intelligent vision-based sensor that detects events,
  - **MQTT protocol** provides the IoT messaging that connects components,
  - **Streamlit** serves as the dashboard that displays and reacts to those events
    
  ... illustrating how modern AI-enabled systems are built from **independent** and **loosely-coupled** services working together.

  <img width="999" height="421" alt="aiot-arch" src="https://github.com/user-attachments/assets/1c107a3e-f58f-4a64-8610-3cc2610cb8dd" />

- **Gesture Recognition Sensing**
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1twePz-VGX2P3IL2JOTqOxQK63IX9UB9L)
  - [Thumb Up Video](https://drive.google.com/file/d/1-x0MmaHBhVoeoj8cWHOklkmO-efb-TgS/view?usp=drive_link)
  - [Thumb Down Video](https://drive.google.com/file/d/1GoFYS3_CaZotuZ5BxdKjzWr9rFpW_mo1/view?usp=sharing)
    
- **Gaze Detection Sensing**
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1V5cbNkvrQoyiFDRlgqPpR7QbIqXrhvfv)
  - [Gradually facing camera Video](https://drive.google.com/file/d/1XV3mZpf8SK9bMKwdb4pU5izpPdrZhUyG/view?usp=sharing)
    
- **Person Detection Sensing**
  - [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1l0euXnNbQuUfrc_V882zkoIlMr9fLikD)
  - [Man walking in and out of room Video](https://drive.google.com/file/d/1qLhuFXLVMNy_hB4aqe90t6YUitm80XHD/view?usp=sharing)
  
- **Streamlit Frontend via VScode**
  - Follow instructions in [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nuZchxeoMemQZRmbtFbOOtCMJm2uXpcp) to setup a Streamlit dashboard and MQTT listener on your local machine (Microsoft Windows)
  
### 6. Capstone Project Development (July 9)
### 7. Exhibition Day Rehearsals (July 16)
### 8. Exhibition Day (July 23)
