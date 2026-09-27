# Final Project

This is my TensorFlow image-classification project. I used MobileNetV2 to recognize five kinds of flowers, first with feature extraction and then with fine-tuning. The notebook also shows the training results and predictions on test images.

## Run the notebook

Open `Final project.ipynb` in VS Code, choose the Python environment in `.venv`, and select **Run All**. On the first run, it downloads the flower photos and the pretrained MobileNetV2 weights.

To set up the environment:

```bash
python3 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
```
