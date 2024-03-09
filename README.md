• DOMAIN: Automotive Surveillance.
• CONTEXT: 
Computer vision can be used to automate supervision and generate action appropriate action trigger if the event is 
predicted from the image of interest. For example a car moving on the road can be easily identified by a camera as make of 
the car, type, colour, number plates etc.
• DATA DESCRIPTION:
The Cars dataset contains 16,185 images of 196 classes of cars. The data is split into 8,144 training images and 8,041 testing 
images, where each class has been split roughly in a 50-50 split. Classes are typically at the level of Make, Model, Year, e.g. 
2012 Tesla Model S or 2012 BMW M3 coupe.
Data description: 
‣ Train Images: Consists of real images of cars as per the make and year of the car. 
‣ Test Images: Consists of real images of cars as per the make and year of the car.
‣ Train Annotation: Consists of bounding box region for training images.
‣ Test Annotation: Consists of bounding box region for testing images.
Dataset has been attached along with this project. Please use the same for this capstone project.
Original link to the dataset for your reference only: https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder [ for your 
reference only ]
Reference: 3D Object Representations for Fine-Grained Categorisation, Jonathan Krause, Michael Stark, Jia Deng, Li Fei-Fei 4th IEEE 
Workshop on 3D Representation and Recognition, at ICCV 2013 (3dRR-13). Sydney, Australia. Dec. 8, 2013.
• PROJECT OBJECTIVE: Design a DL based car identification model.
• PROJECT TASK: [ Score: 100 points]
1. Milestone 1: [ Score: 40 points]
‣ Input: Context and Dataset
‣ Process: 
‣ Step 1: Import the data. [ 3 points ]
‣ Step 2: Map training and testing images to its classes. [ 6 points ]
‣ Step 3: Map training and testing images to its annotations. [ 6 points ]
‣ Step 4: Display images with bounding box. [ 5 points ]
‣ Step 5: Design, train and test basic CNN models to classify the car. [ 10 points ]
‣ Step 6: Interim report [ 10 points ]
‣ Submission: Interim report, Jupyter Notebook with all the steps in Milestone-1
2. Milestone 2: [ Score: 60 points]
‣ Input: Preprocessed output from Milestone-1
‣ Process: 
‣ Step 1: Fine tune the trained basic CNN models to classify the car. [ 5 points ]
‣ Step 2: Design, train and test RCNN & its hybrids based object detection models to impose the bounding box or 
mask over the area of interest. [ 10 points ]
‣ Step 3: Pickle the model for future prediction [ 5 Points]
‣ Step 4: Final Report [40 Points]
