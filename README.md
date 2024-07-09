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

## Project Structure

```
├── data/
│   ├── helmets/
│   ├── triple_riding/
│   ├── mobile_usage/
│   ├── overspeeding/
├── models/
│   ├── yolov3.cfg
│   ├── yolov3.weights
│   ├── yolov3.yaml
├── notebooks/
│   ├── Data_Preprocessing.ipynb
│   ├── Model_Training.ipynb
├── src/
│   ├── detection.py
│   ├── speed_detection.py
│   ├── utils.py
├── static/
│   ├── detections/
│   ├── uploads/
├── templates/
│   ├── index.html
│   ├── uploaded.html
├── .gitignore
├── LICENSE
├── README.md
├── app.py
├── requirements.txt
```

## Usage

1. **Installation**:
   - Clone the repository and navigate into it.
   - Set up a virtual environment and install dependencies.

2. **Running the App**:
   - Run `python app.py`.
   - Open your web browser and go to `http://localhost:5000`.

3. **Upload an Image**:
   - Choose an image file containing traffic scenes.
   - Click "Upload" to detect violations.

4. **View Results**:
   - See detected objects and violations overlaid on the uploaded image.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Publication

This project has been published as part of a research paper. For more details, refer to our [IEEE publication](https://ieeexplore.ieee.org/document/10112954#citations).
