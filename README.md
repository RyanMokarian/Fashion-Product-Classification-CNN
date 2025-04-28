# Fashion Product Image Classification Using CNN

This project implements a Convolutional Neural Network (CNN) model to classify fashion product images into 13 subcategories:

**Subcategories:**
- Topwear
- Bottomwear
- Innerwear
- Bags
- Watches
- Jewellery
- Eyewear
- Wallets
- Shoes
- Sandal
- Makeup
- Fragrance
- Others

## Dataset
The project uses the [Fashion Product Images Small Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small) from Kaggle.

**Dataset Download:**  
- The dataset is downloaded programmatically inside the Colab notebook using the Kaggle API.
- Instructions to set up Kaggle API access (uploading `kaggle.json`) are included in the notebook.

**Data Preparation:**
- After downloading, the images are organized into training, validation, and testing sets based on `train.csv` and `test.csv` metadata files.

## Project Structure
- **Kaggle API Authentication:** Upload `kaggle.json` to access Kaggle dataset.
- **CNN Model:** Custom-built Convolutional Neural Network for image classification.
- **Motivation:** Model structure is based on balancing training efficiency and generalization ability.
- **Training and Evaluation:** Model is trained and evaluated, with results reported on training, validation, and test sets.

## Files
- Images folder
- styles.csv (metadata)
