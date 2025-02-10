# CNN Visualization and Interpretation

## Overview
This project explores visualization techniques to interpret how Convolutional Neural Networks (CNNs) make predictions. It includes occlusion analysis and filter visualization to analyze feature extraction at different layers of a pretrained model.

## Features
- **Dataset Handling**: Utilizes `torchvision.datasets` with a custom folder of images.
- **Pretrained Model**: Uses models from `torchvision` for image classification and feature extraction.
- **Occlusion Analysis**: Identifies important regions in an image by systematically blocking parts of the input and observing changes in predictions.
- **Filter Visualization**: Displays feature maps at different convolutional layers to understand feature learning.
- **Data Preprocessing**: Implements image resizing, normalization, and augmentation using `torchvision.transforms`.
- **Visualization**: Uses `matplotlib` and `seaborn` for intuitive feature map visualization.

## Installation
### Requirements
Ensure you have Python installed along with the following dependencies:
```bash
pip install torch torchvision numpy matplotlib seaborn
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CNNVisualization.git
   cd CNNVisualization
   ```
2. Unzip and place your dataset in the `data/` directory.
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook CNNVisualisation.ipynb
   ```

## Results
- **Occlusion Sensitivity**: Visualizes regions that influence model predictions.
- **Filter Activations**: Displays convolutional layer activations for better interpretability.

## Contributing
Feel free to fork this repository, improve the visualization techniques, and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

