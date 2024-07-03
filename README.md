# Five cool things you can do with Embeddings using FiftyOne!

## Setup

Make sure you have FiftyOne installed:

```python
pip install fiftyone
```

Once you've installed FiftyOne, you'll need to run the following commands to install the required plug-ins:

```
fiftyone plugins download https://github.com/jacobmarks/zero-shot-prediction-plugin

fiftyone plugins requirements @jacobmarks/zero_shot_prediction --install

fiftyone plugins download https://github.com/jacobmarks/reverse-image-search-plugin

fiftyone plugins requirements @jacobmarks/reverse_image_search --install

fiftyone plugins download https://github.com/jacobmarks/semantic-document-search-plugin

fiftyone plugins requirements @jacobmarks/semantic_document_search --install

fiftyone plugins download https://github.com/jacobmarks/pytesseract-ocr-plugin

fiftyone plugins requirements @jacobmarks/pytesseract_ocr --install

```

You'll also need to install `umap-learn`, `replicate`, and `ultralytics`:

```python
pip install umap-learn replicate ultralytics
```