# Recommendation AI And Custom CNN
For the class: 3.1 BDT ML With Big Data

This class existed of two parts. Using unsupervised learning equations for movie recommendation systems, and designing a custom CNN to recognize hieroglyphs in images.

**Active Development:** 2024-09-09 - 2024-11-08<br>
**Last Change:** 2024-11-08<br>

| | |
| :---: | :---: |
| ![](/Screenshots/1-User_Based.png) | ![](/Screenshots/2-CNN.png) |

## Hieroglyph CNN
We experimented with different layer configurations and RL techniques to create a CNN model that best classifies hieroglyphs. These are the same hieroglyphs used in the [Hieroglyph Recognizer](https://github.com/Emanuel-de-Jong/Saxion-Hieroglyph-Recognizer).

To run it for yourself, download the hieroglyph images [here](https://github.com/Emanuel-de-Jong/Saxion-Recommendation-AI-And-Custom-CNN/releases/tag/hieroglyphs) and extract them in `Hieroglyph CNN/dataset-images`. Then run `cnn.ipynb`.

## Movie Recommendation Models
These are multiple movie UL recommendation algorithms. A content based and a user based system is implemented. Multiple similarity algorithms are tested to find the best fitting one. Since the dataset is large, efficiency during training and inference are taken into account.

To run it for yourself, download the dataset [here](https://github.com/Emanuel-de-Jong/Saxion-Recommendation-AI-And-Custom-CNN/releases/tag/movie-dataset) and extract it in `Movie Recommendation Models/dataset`. Then run the desired notebook.
