# BISINDO YOLOv8 Model

Sign Language Recognition Model untuk Bahasa Isyarat Indonesia (BISINDO)

## Model Details
- **Architecture**: YOLOv8s
- **Classes**: 26 (A-Z)
- **Input Size**: 640x640
- **Accuracy**: 97.53% mAP
- **Format**: TensorFlow.js

## Usage
```javascript
import * as tf from '@tensorflow/tfjs';

const model = await tf.loadGraphModel(
  'https://yourusername.github.io/bisindo-yolov8-model/model/model.json'
);