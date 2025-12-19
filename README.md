# Black Aphid Detection using Deep Learning

This repository presents a practice deep learning project for detecting black aphids on sticky traps in greenhouse environments using the YOLO object detection framework. The project is intended as a technical portfolio and learning exercise, focusing on model training, evaluation, and visualization rather than proposing a new dataset or biological discovery.

**Important note:**  
The dataset used in this project originates from prior research and is not newly collected by the author of this repository.

## Reference Dataset Source

Kapetas, D., Christakakis, P., Faliagka, S., Katsoulas, N., & Pechlivani, E. M. (2025).  
*AI-Driven Insect Detection, Real-Time Monitoring, and Population Forecasting in Greenhouses.*  
AgriEngineering, 7(2), 29.  
https://doi.org/10.3390/agriengineering7020029

## Project Scope

- Object detection of black aphids on yellow sticky traps
- Single-class detection (black aphid)
- High-resolution image training and inference
- Visual comparison between ground truth annotations and model predictions

## Model

- YOLO11s (Ultralytics implementation)
- Single-class object detection
- Transfer learning from pretrained weights
- Evaluation using standard detection metrics (Precision, Recall, mAP)

## Training Environment

- Platform: Kaggle Notebook
- GPU: NVIDIA Tesla P100
- Training configuration adjusted to hardware constraints (e.g., small batch size)

## How to Run

1. Open the notebook in a Kaggle or compatible Python environment
2. Place the dataset according to the paths specified in the notebook
3. Run training, validation, and inference cells sequentially
4. Visualization outputs include:
   - training metrics plots
   - ground truth vs prediction comparisons
   - sample detection results

## Notes

- Dependency versions are not strictly specified, as this repository is intended for demonstration and portfolio purposes only.
- Reported metrics may vary between runs due to stochastic training behavior and hardware constraints.
- Class names follow YOLO indexing internally (e.g., class `0`), with human-readable labels applied during visualization.

## License and Usage

This project is shared for **educational and portfolio purposes only**.  
All credit for the original dataset and experimental concept belongs to the cited prior research.
