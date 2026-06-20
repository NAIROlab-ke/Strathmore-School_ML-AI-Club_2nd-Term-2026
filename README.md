# Junior Student Group (YOLO)

### 1. AI Ecosystem, Part 1 (May 7 - 14)
- [Colab and Linux CLI, Introduction](https://colab.research.google.com/drive/1MbQ_D4J1lOiqfEmNwLnFpiD-gqmnXmk3)
- [Face Detection with YOLO on Colab](https://colab.research.google.com/drive/1ZFKzxWIkEe3ptxmgcRDKUSZeGNW1KVMN#scrollTo=148eRPF04odg)
- Training Dataset
  - [v2.v2i.yolov8-face-detection-data.zip](https://www.dropbox.com/scl/fi/f1hvkvjk1fe3qx5ze84gv/v2.v2i.yolov8-face-detection-data.zip?rlkey=msa8tjdedg2bpe34a272lzdrw&st=rr7ygsbp&dl=0)
    
    **NOTE:** This is a random dataset obtained from the [Roboflow Universe](https://universe.roboflow.com/). It hasn't been inspected for correctness or appropriateness. Feel free to use any other dataset of your choice.
    
- Test Data
  - [face-1-480p.mp4](https://www.dropbox.com/scl/fi/b1qfc1drqeut3hcq7h9ad/face-1-480p.mp4?rlkey=krg9y3fqxjzf8rwxjot1b1akc&st=if1ky3xe&dl=0)
  - [faces-image.jpeg](https://www.dropbox.com/scl/fi/4kmw6ta04pv43lk59at78/faces-image.jpeg?rlkey=vx6jozeggjmetpl8dexnia7yx&st=fzvuwnhg&dl=0)

### 2. AI Ecosystem,  Part 2 (May 21/28)
- **Watch this first!** [**Roboflow + Google Drive + Google Colab Training Pipleline Tutorial**](https://colab.research.google.com/drive/1ZFKzxWIkEe3ptxmgcRDKUSZeGNW1KVMN#scrollTo=148eRPF04odg)
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
- [Google Colab Notebook](https://colab.research.google.com/drive/1Ywn4LSUa_OqYuXnMtqHCg5Ub_w7NcRDq?usp=drive_link)

### 4. Football Player Detection, (June 18)
- Introduce the concept of **fine-tuning** a **pre-trained** model
  - Ultralyitics YOLO is a pre-trained model that can detect upto 80 classes out-of-the-box -- including "person" (i.e human) and field sports balls (football, volleyball, basketball, etc)
  - Fine-tuning allows the pre-trained model to be used to detect classes that it was not originally trained for -- and even enhancing performance of trained classes  
- Objective is to fine-tune a YOLO model
  - distinguish between football players, goalkeepers, and refeeres (i.e. 3 new classes from the otherwise same "person" class)
  - improve football detection
- Inference results
  - Fine-tuned model should detect only 4 classes: player, referee, goalkeeper, ball
  - Other humans previously detected by pre-trained model (i.e. "human" class) should be ignored
- Lab
  - [Google Colab Notebook](https://colab.research.google.com/drive/1QXV9V6PGTMjLT1cSG44Xlw0b9atwr_7E?usp=drive_link)
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
### 5. Exhibition Day Capstone Project Brainstorming (July 9)
- Project Ideas
  - AI Vision-based Realtime Analysis of Strathmore School Field Sports
  - Autopilot traffic-light and road-sign recognition (DonkeyCar Platform)

### 6. Exhibition Day Rehearsals (July 16)
### 7. Exhibition Day (July 23)

<br><br>

# Senior Student Group (MediaPipe)

### 1. [Introduction to Python](https://colab.research.google.com/drive/1Xjif0l1T265o3CJGt48gxgq462lQq1ng?usp=sharing) (May 7th/14th)
### 2. [Internet of Things (IoT) Protocols with Python](https://colab.research.google.com/drive/1OeXjPPn027Rxyq0Wdg72c1fCaw8uuCR9) (May 21th)     
### 3. [Streamlit](https://colab.research.google.com/drive/1wVZIgjYCBR95nNL-ynEgySJZR4MN96mN#scrollTo=kOSTeKHPsDNJ)  (June 4)
### 4. MediaPipe API (June 18th)
- Object Detection
  - [Notebook](https://colab.research.google.com/drive/1RBEKU4mP8_T52Q8IDljfTPWMY9IjCbqF?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1n0w5rwSewhPGay13mRt3GItH4coWWybD/view?usp=sharing)
- Face Detection
  - [Notebook](https://colab.research.google.com/drive/1HUIvbgDdP1Pm5kB16Zqhu1JXtuGG_2R9?usp=drive_link)
  - [Test Video 0](https://drive.google.com/file/d/1sPKL8GDBxEc017sYRgIHjuSquqgcdq5E/view?usp=sharing)
  - [Test Video 1](https://drive.google.com/file/d/19lJL-3Tesa9liDVnTQtPHZCERvRvsyaf/view?usp=sharing)
  - [Test Video 2](https://drive.google.com/file/d/1VIxy4oOr9bEA8-0rrIs0eCCCVDdSLjiu/view?usp=sharing)
  - [Test Video 3](https://drive.google.com/file/d/1EKW8PCeh33p2FeeKErnwUQVsV4T7vYoA/view?usp=sharing)
- Face Landmark Detection
  - [Notebook](https://colab.research.google.com/drive/1_5AgOQooE9SZJF5SIsVmPnatNQbugmCY?usp=drive_link)
  - [Test Video 0](https://drive.google.com/file/d/19lJL-3Tesa9liDVnTQtPHZCERvRvsyaf/view?usp=sharing)
  - [Test Video 1](https://drive.google.com/file/d/1VIxy4oOr9bEA8-0rrIs0eCCCVDdSLjiu/view?usp=sharing)
- Hand Landmark Detection
  - [Notebook](https://colab.research.google.com/drive/1Bn63vY6i3cBeE94bUDptUu4DbiKwQGNM?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1WmNtTK48xNdWgn4e9YWFqnuotQiW5O8X/view?usp=sharing)     
- Gesture Recognition
  - [Notebook](https://colab.research.google.com/drive/1AqW_c0ofphjoLQzyHyCQdOjWWbVwY8p2?usp=drive_link)
  - [Test Video](https://drive.google.com/file/d/1WmNtTK48xNdWgn4e9YWFqnuotQiW5O8X/view?usp=sharing)
- Pose Landmark Detection
  - [Notebook](https://colab.research.google.com/drive/1PiNBxNATMRdzbg21hVHZNPYgfOknVUNE?usp=drive_link)
  - [Test Video 0](https://drive.google.com/file/d/1P_qjE2pHV_mFSn3zfSSkdt-9sHTMNngA/view?usp=sharing)
  - [Test Video 1](https://drive.google.com/file/d/1K2BS0wv9tOaMjyaCDQK2X4DMYyAKtvEB/view?usp=sharing)
### 5. App Development, (June 25th)
- Lights control with hand gestures
- Volume control with hand gestures
### 6. Exhibition Day Capstone Project Brainstorming (July 2)
- Project Ideas
  - Vision-based RC Car Control (Raspberry Pi)
  - AI Vision Smart CCTV with IoT integrations (Raspberry Pi)
    <!--
      1. Prolonged raised hands pose-estimation signals possible distress.
         Could trigger silent alarm and security protocol e.g. phone call with code word for affirmation
      2. Pose-estimation in addition to face/body detection for human target counting
      3. Gesture control
     -->
### 7. Capstone Project Development (July 9)
### 8. Exhibition Day Rehearsals (July 16)
### 9. Exhibition Day (July 23)
