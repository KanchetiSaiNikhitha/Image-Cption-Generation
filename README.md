# Traffic-Detection-System using YOLO V9
This project implements a Traffic Detection System using the YOLO v9 architecture. The system is designed to detect and classify vehicles in real-time from video feeds or images, utilizing the advanced capabilities of YOLO v9 for object detection.

Features
Real-time Traffic Detection: Identifies and classifies vehicles such as cars, trucks, and motorcycles.
High Accuracy: Utilizes YOLO v9's enhanced model for precise object detection.
Scalable for Various Environments: Can be adapted for different types of traffic scenarios.
Prerequisites
Before running the project, ensure that your environment meets the following requirements:

GPU Access: A compatible NVIDIA GPU is recommended for efficient processing. You can check GPU availability with the nvidia-smi command.
Python 3.7+: Make sure Python is installed.
YOLO v9 Framework: Install the necessary dependencies for YOLO v9.
Installation
1. Clone the repository:
`git clone https://github.com/YourUsername/Traffic-Detection-System.git
cd Traffic-Detection-System`
2. Install the required dependencies:
`pip install -r requirements.txt`
3. Set up the environment:
Ensure your hardware accelerator is set to GPU for optimal performance.
Define the HOME directory in the notebook or script:
`import os
HOME = os.getcwd()
print(HOME)
`
Usage
Prepare the dataset: Place your training and test datasets in the appropriate directories.
Run the notebook: Open the Jupyter notebook and execute the cells to train the model and perform traffic detection.
Inference: Use the trained model to detect traffic in your test videos or images.
Results
The results of the traffic detection are displayed in real-time, showcasing the capability of YOLO v9 in handling dynamic and complex traffic scenarios.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the developers of YOLO v9.
Thanks to NVIDIA for providing the GPU resources.


