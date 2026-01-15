# 🌴 **Oil Palm Tree Health Detection from Drone Imagery Using YOLO11**

## 📝 Project Overview

## ❗️Problem Statement

Oil palm plantation monitoring is traditionally carried out through manual visual inspection, which presents several operational challenges. This process is labor-intensive, as plantation workers are required to physically inspect individual trees, demanding significant manpower and physical effort. In large-scale plantations, this approach becomes increasingly impractical. 

In addition, manual inspection is time-consuming, often requiring hours or even days to assess extensive plantation areas. This slows down decision-making processes and limits the frequency of monitoring, reducing the ability to detect emerging health issues early. 

The assessment of tree health is also subjective and inconsistent, as judgements of healthy versus unhealthy trees can vary between workers depending on their experience and expertise. Such variability leads to inconsistent and error-prone evaluations, increasing the likelihood of misclassification. 
As a result of these limitations, overall productivity is reduced, since delayed or inaccurate inspections can postpone necessary treatment or maintenance actions. This may ultimately lead to reduced yield and the progression of unhealthy crop conditions across the plantation. 

## 🎯 Project Objectives

1. To develop an object detection model that can automatically identify individual oil palm trees and classify each one as Healthy or Unhealthy. 

2. To understand how oil palm trees can be detected using drone imagery and visual characteristics of the tree canopy. 

3. To provide a practical tool that helps plantation workers and agronomists monitor tree health more efficiently and make better, data-driven management decisions.

## 🚀 Getting Started

### Preliminaries

1. **Python 3.10+**: Please ensure that Python 3.10 or higher is installed on your system before running this project. You can download the required version from the official website [Install Python](https://www.python.org/downloads/).

### Setting Up the Environment

1. Clone the repository by running the following command in your terminal:
    ```
    https://github.com/naqibsyahmi/oil-palm-tree-health-detection-yolo11.git
    ```

2. Create a virtual environment named **`venv`** in your project folder by running the following command:

    - **On Windows:**
    ```
    python -m venv venv
    ```

    - **On macOS/Linux:**
    ```
    python3 -m venv venv
    ```

3. Activate the virtual environment based on your operating system:

    - **On Windows:**
    ```
    venv\Scripts\activate
    ```

    - **On macOS/Linux:**
    ```
    source venv/bin/activate
    ```

4. Once the virtual environment is successfully created and activated, run the following command in your terminal to install the required packages:

    - **On Windows:**
    ```
    pip install -r requirements.txt
    ```

    - **On macOS/Linux:**
    ```
    pip3 install -r requirements.txt
    ```

### Running the System

1. Run the following command to execute the notebook to download the dataset
    ```
    jupyter nbconvert --to notebook --execute import_dataset.ipynb --inplace
    ```

2. Navigate to the **`src`** folder by running the following command in your terminal:
    ```
    cd src
    ```

3. Run the **`Oil_Palm_Tree_Health.ipynb`** notebook to run the analysis:
