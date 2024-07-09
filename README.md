# Traffic-Rules-Violation-Detection

This project aims to detect and classify various traffic violations using computer vision techniques. It includes detection for the following violations:

- **No Helmet Violation**
- **Triple Riding Violation**
- **Mobile Phone Usage Violation**
- **Overspeeding Violation**

## Features

- **Object Detection**: Utilizes YOLOv3 for real-time object detection and classification.
- **Speed Detection**: Estimates vehicle speed using computer vision techniques.
- **Custom Dataset**: Includes custom datasets for training and evaluation.

### Directory Structure Details

- **data/**: Contains datasets for different violations.
  - `helmets/`: Dataset for helmet usage detection.
  - `triple_riding/`: Dataset for triple riding detection.
  - `mobile_usage/`: Dataset for mobile phone usage while driving detection.
  - `overspeeding/`: Dataset for overspeeding detection.
  
- **models/**: Includes YOLOv3 model configuration, weights, and YAML file.
  - `yolov3.cfg`: YOLOv3 model configuration file.
  - `yolov3.weights`: Pre-trained YOLOv3 weights.
  - `yolov3.yaml`: YOLOv3 configuration YAML file.

- **notebooks/**: Jupyter notebooks for data preprocessing and model training.
  - `Bounding_the_images.ipynb`: Notebook for data preprocessing steps.
  - `Object_Detection_using_YOLO.ipynb`: Notebook for object detection model.
  - `Training.ipynb`: Notebook for training the detection models.
  - `Triple_Riding.ipynb`: Notebook for triple riding model.
  - `Violation_Detection.ipynb`: Notebook for violation detection model.
  - `yolo_detection_script.ipynb`: Notebook for yolov3 and yolov5 models.


- **.gitignore**: Git ignore file to exclude certain files and directories from version control.
- **LICENSE**: License information for the project.
- **README.md**: This file, containing an overview of the project and setup instructions.
  
## Contributing

Contributions are welcome! Fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Publication

This project has been published as part of a research paper. For more details, refer to our [IEEE publication](https://ieeexplore.ieee.org/document/10112954#citations).
