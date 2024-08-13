# About Me

I’m a 20-year-old junior at the University of Florida who loves computer graphics. At 14 I began self-learning visual effects with Adobe After Effects and Blender, which led to founding Effxcts LLC— a sports VFX company that has worked with clients like ESPN, Bleacher Report, Red Bull, and the Dallas Mavericks. In college, I quickly developed a deep interest in coding, image processing, computer vision, and really all the visual aspects of computer science. This past summer, I interned as a machine learning software engineer at the Children's Hospital of Philadelphia, applying image processing and ML to predict surgical necessity from renal scans. I’m currently working on publishing these results, exploring new interests in the world of computer graphics, and am seeking a summer 2025 internship.

Outside of computer graphics, I enjoy basketball, flag-football, skiing, and ___.

## Current Interests & Projects
### 4D Gaussian splatting
Building a pipeline to turn videos into animated 3D visualizations using Gaussian splatting, with a focus on sports applications. Inspired by the Olympics 2024 'bullet time' 3D static replay.

### Pose estimation for automatic video creation
Creating a program automates creating a video like (this) utilizing pose estimation and machine learning. Web scraping -> identify verification -> sort and filter by pose estimation -> segment the athlete -> generate video. 

## Past Projects
### Renogram Analysis & Surgical Decision-Making with Deep Learning
During my internship at the Children's Hospital of Philadelphia, I led the development of an image processing pipeline in Python, designed to extract quantitative data from over 300 renogram images. This data, including 34 extracted features and 121 points of normalized time-series data, was used to train predictive models, such as logistic regression, random forest, and a convolutional neural network with long short term memory, all aimed at improving surgical decision-making for kidney hydronephrosis. These models were validated using a custom 5-fold cross-validation strategy, ensuring unbiased evaluation, and combined into an ensemble model that achieved an impressive AUROC of 0.90. To enhance clinical utility, I developed two interactive web tools using REST APIs: one enabling clinicians to upload renogram images for automated analysis and another allowing users to draw renogram curves for model interpretability (see here). 


### Basketball shot tracker using ML & computer vision
I engineered a real-time basketball shot tracker using YOLOv8, with enhanced training and inference speeds by over 20x through CUDA optimization. The project achieved 95% score detection accuracy and 97% shot attempt accuracy.

### 3D Illusion
I created an algorithm that adjusts 2D layers based on real-time eye tracking data to simulate 3D depth on a 2D screen. This project combined computer vision with real-time interaction, using OpenCV for facial tracking and CUDA for seamless performance at 60 fps.

### NBA Blender 3D Data Visualization
I developed a Python GUI that visualizes NBA player shooting heat maps by extracting and parsing data from the NBA API. The data was then processed in Blender, where I scripted over 500 3D models to follow physics-based shooting arcs. This project explored the intersection of sports data and 3D visualization, resulting in a viral data visualization with over 4 million views.
