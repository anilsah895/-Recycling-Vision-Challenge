# -Recycling-Vision-Challenge
Project:Recycling Vision Challenge

Files included:
- Python notebook / source code
- Saved model files
- CSV result summaries
- Any generated plots or outputs

Required libraries:
- Python 3.x
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- Pillow

Dataset structure expected:
dataset/
    train/
    val/
    test/
    noisy-test/

How to run:
1. Place the dataset in the correct directory or update the dataset path in the code.
2. Install the required libraries.
3. Run all notebook cells in order.
4. The notebook will train the baseline model, fine-tune the improved model, evaluate all splits, and export result CSV files.

Outputs:
- Saved baseline model
- Saved fine-tuned model
- Training history CSV files
- Results summary CSV
- Misclassified noisy-test CSV
- Confusion matrices and training plots
