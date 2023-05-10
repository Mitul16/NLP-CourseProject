# NLP-CourseProject
Sentence classification using CNN and Entity extraction using NER

## Project Structure
```
./
├── datasets/
│   ├── large-movie-dataset/train/
│   ├── large-movie-dataset/test/
├── models/
├── src/
│   ├── NamedEntityRecognition.ipynb
│   ├── NewsAPI.ipynb
│   ├── Project.ipynb
│   └── TextClassification.ipynb
├── requirements.txt
└── README.md
```

### Description
```
datasets/:
To keep all the datasets in one place

datasets/large-movie-dataset/:
IMDb movie review dataset

models/:
To keep all the trained models for sentence classification and attribute extraction tasks

src/:
Source code for this project

requirements.txt:
List of required dependencies with their versions

README.md:
This file
```

## Usage
### Clone the repository
```bash
git clone https://github.com/Mitul16/NLP-CourseProject.git
```

### Install the dependencies
```bash
cd NLP-CourseProject
pip install -r requirements.txt
```

### Download the datasets
- IMDb movie review dataset from [here](https://ai.stanford.edu/~amaas/data/sentiment/)

### Run any of the Jupyter Notebooks
Each notebook already has the code output, please check them.

### Results
The trained models are saved in `./models` directory.

The evaluation metrics such as **loss** and **accuracy** are also displayed in the console during the training and testing phases.