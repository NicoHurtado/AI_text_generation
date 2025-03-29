# Text Generation with LSTM in Keras

This Jupyter Notebook demonstrates a basic **character-level text generation model** using **LSTM (Long Short-Term Memory)** networks in **TensorFlow/Keras**. The model is trained on a text corpus and generates coherent sequences character by character.

### Key Components

- Preprocessing of raw text data using `nltk` and `RegexpTokenizer`
- Vectorization into input/output sequences
- LSTM-based neural network built with `tensorflow.keras`
- Training using RMSprop optimizer
- Text generation with temperature-based sampling

## Requirements

Install required Python libraries:

```bash
pip install -r requirements.txt
```

## How to Use

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open `Text Generation AI.ipynb`.
3. Run all cells to train and test the model.
4. Modify the text corpus or training parameters to experiment with different results.

## Example Use Cases

- Generating creative writing (poetry, fiction)
- Emulating author styles
- Text completion or augmentation

## License

This project was taken from educational tutorials and is for educational and experimental use. Modify and extend freely.
