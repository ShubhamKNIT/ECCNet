# ECCNet

Deep learning experiments for esophageal cancer cell image classification using Keras/TensorFlow. See `FinalReport.pdf` for detailed methodology and results.

## Repository Contents
- **Data**: `Data_Generation.ipynb`
- **Experiments**: `Experiment_Model_AC_DA_GEN_46.ipynb`, `Experiment_ResNet.ipynb`, `Experiment_VGG.ipynb`, `Experiment_VIT.ipynb`
- **Prediction**: `ECCNetPrediction1.ipynb`, `ECCNetPrediction2.ipynb`
- **Models**: `model_ac_da_gen_46.keras`, `model.keras`
- **Report**: `FinalReport.pdf`

## Dataset
- **Source**: cbiocancer
- **Storage**: 
    - Raw Dataset: <a href='https://drive.google.com/file/d/1ICCSyNCVzsdQbTxOz9TDrmJo-M54LVQA/view?usp=drive_link'>Click Here</a>
    - Generated Dataset: <a href='https://drive.google.com/file/d/1e2E8K9s-5j61owKJ8wCIpdZd4e7MFtQD/view?usp=drive_link'>Click Here</a>

To access the dataset in Colab:
```python
from google.colab import drive
drive.mount('/content/drive')
```

## Environment
**Recommended**: Google Colab with T4 GPU

### Setup in Colab
1. Upload notebooks or connect Google Drive
2. Enable GPU: Runtime → Change runtime type → T4 GPU
3. Install dependencies if needed in colab.

## Usage
Load trained models:
```python
import tensorflow as tf
model = tf.keras.models.load_model('model.keras')
```

Run notebooks in Colab or Jupyter and ensure dataset paths are correctly configured.

## References
See `FinalReport.pdf` for complete dataset description, methodology, and experimental results.

## Contact
For questions or collaborations, please open an issue or contact the repository maintainer.
