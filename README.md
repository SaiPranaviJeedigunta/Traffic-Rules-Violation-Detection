# Traffic-Rules-Violation-Detection

Traffic-Rules-Violation-Detection is a project aimed at using computer vision techniques to detect and classify various traffic violations. It leverages object detection and speed estimation methods to enhance traffic monitoring and enforcement.


- **No Helmet Violation**
- **Triple Riding Violation**
- **Mobile Phone Usage Violation**
- **Overspeeding Violation**

## Features

- **Object Detection**: Utilizes YOLOv3 for real-time object detection and classification.
- **Speed Detection**: Estimates vehicle speed using computer vision techniques.
- **Custom Dataset**: Includes custom datasets for training and evaluation.


## Project Structure

├── data/
│   ├── helmets/
│   ├── triple_riding/
│   ├── mobile_usage/
│   └── overspeeding/
├── models/
│   ├── yolov3.cfg
│   ├── yolov3.weights
│   └── yolov3.yaml
├── notebooks/
│   ├── Bounding_the_images.ipynb
│   ├── Object_Detection_using_YOLO.ipynb
│   ├── Training.ipynb
│   ├── Triple_Riding.ipynb
│   ├── Violation_Detection.ipynb
│   └── yolo_detection_script.ipynb
├── .gitignore
├── LICENSE
└── README.md
  
## Contributing

Contributions are welcome! Fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Publication

This project has been published as part of a research paper. For more details, refer to our [IEEE publication](https://ieeexplore.ieee.org/document/10112954#citations).
