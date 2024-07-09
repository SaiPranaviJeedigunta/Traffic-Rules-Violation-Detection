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

echo "### Directory Structure Details" > README.md
echo "\`\`\`" >> README.md
echo "├── data/" >> README.md
echo "│   ├── helmets/" >> README.md
echo "│   ├── triple_riding/" >> README.md
echo "│   ├── mobile_usage/" >> README.md
echo "│   └── overspeeding/" >> README.md
echo "├── models/" >> README.md
echo "│   ├── yolov3.cfg" >> README.md
echo "│   ├── yolov3.weights" >> README.md
echo "│   └── yolov3.yaml" >> README.md
echo "├── notebooks/" >> README.md
echo "│   ├── Bounding_the_images.ipynb" >> README.md
echo "│   ├── Object_Detection_using_YOLO.ipynb" >> README.md
echo "│   ├── Training.ipynb" >> README.md
echo "│   ├── Triple_Riding.ipynb" >> README.md
echo "│   ├── Violation_Detection.ipynb" >> README.md
echo "│   └── yolo_detection_script.ipynb" >> README.md
echo "├── .gitignore" >> README.md
echo "├── LICENSE" >> README.md
echo "└── README.md" >> README.md
echo "\`\`\`" >> README.md


## Contributing

Contributions are welcome! Fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Publication

This project has been published as part of a research paper. For more details, refer to our [IEEE publication](https://ieeexplore.ieee.org/document/10112954#citations).
