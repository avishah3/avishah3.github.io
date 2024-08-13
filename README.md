# About Me

I'm a 20-year-old junior at the University of Florida with a strong focus on computer graphics. I started at 14 by teaching myself visual effects using After Effects and Blender, which eventually led to founding Effxcts LLC— a sports VFX company that’s worked with ESPN, Bleacher Report, Red Bull, the Dallas Mavericks, and more.

In college, my interests expanded to coding, image processing, computer vision, and all the visual aspects of technology. This past summer, I interned as a Machine Learning Software Engineer at the Children's Hospital of Philadelphia, applying image processing and machine learning techniques to predict surgical needs from renogram imaging.

Currently, I’m working on publishing those results, exploring new projects in computer graphics, and seeking a summer 2025 internship to continue advancing in this field.

Outside of computer graphics, I enjoy basketball, flag-football, skiing, and ___.

## Current Interests & Projects
Current interests: 3D Reconstruction, Generative Diffusion Models, Pose Estimation, Tools for VFX artists.

### 4D Gaussian splatting
Building a pipeline to turn videos into animated 3D visualizations using Gaussian splatting, with a focus on sports applications. Inspired by the Olympics 2024 'bullet time' 3D static replay.

### Pose estimation for automatic video creation
Creating a program automates creating a video like (this) utilizing pose estimation and machine learning. Web scraping -> identify verification -> sort and filter by pose estimation -> segment the athlete -> generate video. 

## Past Projects
### Renogram Analysis & Surgical Decision-Making with Deep Learning
During my internship at the Children's Hospital of Philadelphia, I developed an image processing pipeline in Python to extract quantitative data from over 300 renogram images. This data, including 34 extracted features and 121 normalized time-series points, was used to train predictive models such as logistic regression, random forest, and a convolutional neural network with long short-term memory (CNN-LSTM), all aimed at improving surgical decisions for kidney hydronephrosis. Validated with a custom 5-fold cross-validation, these models were combined into an ensemble that achieved an AUROC of 0.90. To enhance clinical utility, I also developed two interactive web tools using REST APIs: one for automated renogram analysis and another for drawing renogram curves to aid in model interpretability (see here).


### Basketball shot tracker using ML & computer vision
I engineered a real-time basketball shot tracker using YOLOv8, with enhanced training and inference speeds by over 20x through CUDA optimization. The project achieved 95% score detection accuracy and 97% shot attempt accuracy.

### 3D Illusion
I created an algorithm that adjusts 2D layers based on real-time eye tracking data to simulate 3D depth on a 2D screen. This project combined computer vision with real-time interaction, using OpenCV for facial tracking and CUDA for seamless performance at 60 fps.

### NBA Blender 3D Data Visualization
I developed a Python GUI that visualizes NBA player shooting heat maps by extracting and parsing data from the NBA API. The data was then processed in Blender, where I scripted over 500 3D models to follow physics-based shooting arcs. This project explored the intersection of sports data and 3D visualization, resulting in a viral data visualization with over 4 million views.
