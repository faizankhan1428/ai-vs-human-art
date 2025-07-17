# AI vs Human Art – Dataset Creation Notebook

This notebook builds a labeled image dataset that distinguishes between AI-generated art and Human-made art. It collects, organizes, and prepares image files from public sources, assigning clear labels (`AI` or `Human`) for supervised learning tasks.

## Contents
- Download and organize AI-generated images (e.g., from open-source platforms such as Stable Diffusion, MidJourney)
- Collect human-made artwork from public datasets and repositories
- Label each image with either "AI" or "Human" for binary classification
- Clean file names, resize images, and structure the folder hierarchy
- Export the final dataset in a well-structured format

## Use Cases
- Binary image classification (AI vs Human)
- Visual Turing test experiments
- Evaluation of generative models (GANs, diffusion models)
- Research on visual patterns in AI-generated vs human-created art

## Dataset Output Structure

The final dataset contains two folders:
/AI
/Human

Each folder includes labeled images ready for training machine learning and deep learning models.

## How to Use
1. Clone this repository or open the notebook in Kaggle
2. Follow the steps in the notebook to generate or load images
3. Run all cells to preprocess and label the images
4. Download or share the dataset via Kaggle Datasets

## Next Steps
You can use this dataset to:
- Train convolutional neural networks (CNNs)
- Build a web-based quiz or application
- Evaluate AI image generation methods
- Conduct explainability analysis

---

Created by Muhammad Faizan  
[Kaggle Profile](https://www.kaggle.com/faizankhandeshmukh)
