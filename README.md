<h1 align="center">Tomato Disease Finder</h1>

<p align="center">
  <img src="https://media4.giphy.com/media/a0N6ZmPmzGIPm/giphy.gif?cid=ecf05e47uygzutc57k7q8glhwc95xcjtvdsvk5jpvitdvwre&rid=giphy.gif&ct=g" alt="tomato  image">
</p>

A plant disease detector photo app is a mobile application that allows users to identify and diagnose plant diseases by taking a photograph of the affected plant. The app uses artificial intelligence and machine learning algorithms to analyze the photograph and provide a diagnosis based on the visual characteristics of the plant disease.

To use the app, the user would take a photograph of the affected plant and upload it to the app. The app would then analyze the photograph and provide a diagnosis of the plant disease based on its visual characteristics, such as the presence of certain symptoms or patterns on the plant. The app may also provide information about the causes of the plant disease and suggest potential treatments or remedies.

Some plant disease detector photo apps may also include features such as a plant encyclopedia, which provides information about different plant species and their care requirements, or a plant disease encyclopedia, which provides information about common plant diseases and how to prevent and treat them.

Overall, a plant disease detector photo app can be a useful tool for gardeners and plant enthusiasts who want to identify and diagnose plant diseases in order to take appropriate action to treat and prevent them.

## Prerequisites

Before contributing or adding a new feature, Please make sure you have already installed the following tools:

- [Git](https://git-scm.com/downloads)
- [Python](https://www.python.org/downloads/)
- [DataSet](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)

## Installation Steps

1. **Download Dataset**
from here --> [Dataset](https://www.kaggle.com/datasets/noulam/tomato)
2. **download test.ipynb file**
3. **maintain folder structure at like this**
```
Main/
├── train/
│   ├── Tomato___Bacterial_spot
│   ├── Tomato__Early_blight
│   ├── ...
│   └── Tomato___Tomato_Yellow_Leaf_Curl_Virus
├── valid/
│   ├── Tomato___Bacterial_spot
│   ├── Tomato__Early_blight
│   ├── ...
│   └── Tomato___Tomato_Yellow_Leaf_Curl_Virus
├── test.ipynb
```
5. **Create a Conda environment:**
   ```
   conda create --name myenv
   ```

6. **Activate the environment:**
   - For Windows:
     ```
     conda activate myenv
     ```
   - For macOS/Linux:
     ```
     source activate myenv
     ```

7. **Install dependencies:**
   ```
   conda install <package_name>
   ```

8. **Install packages using pip (if not available in conda):**
   ```
   pip install <package_name>
   ```

9. **Run Jupyter Notebook:**
   ```
   jupyter notebook
   ```

## Contributors

[![Contributors](https://contrib.rocks/image?repo=ranjitodedra/cleantomato)](https://github.com/ranjitodedra/cleantomato/graphs/contributors)

Managed by [Ranjit Odedra](https://github.com/ranjitodedra) 
