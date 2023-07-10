# Sepsis_Prediction_with Machine_Learning_and_FASTAPI
Build Machine Learning Model with FastAPI

### My Online Presence
![GitHub](https://github.com/nhavim) ![Medium Articles](https://medium.com/@nhavim123) ![LinkedIn](https://www.linkedin.com/in/nathaniel-havim)

![Cover_Image](https://my.clevelandclinic.org/-/scassets/images/org/health/articles/12361-sepsis)

### Introduction
This project focuses on predicting sepsis disease using data collected on patients based on classification machine learning techniques and FastAPI to build a simple but user-friendly app for real-time prediction for early detection of the sepsis condition among patients.

### Description
The dataset used contains a list of patients in a hospital and their attributes and whether the patient is positive for Sepssis or not.
Sepsis is a severe and potentially life-threatening condition that occurs when the body's response to infection triggers widespread inflammation. It is often referred to as blood poisoning.
The aim of this project is to explore the various factors that can cause sepsis in order to predict the occurrence of sepsis.
Predicting sepsis is important because early recognition and intervention can significantly improve patient outcomes. Sepsis can progress rapidly and become life-threatening within a short period. By identifying patients who are at risk of developing sepsis, healthcare providers can initiate timely treatment and interventions to prevent the condition from worsening.

#### Overview of Dataset
The dataset contained the following information.
| Column Name	 |Target	 |Description            |
|--------------|---------|-----------------------|
|  ID	         | N/A	   | Unique number to represent patient ID |
|  PRG	       | False   | Plasma glucose |
|  PL	         | False   | Blood Work Result-1 (mu U/ml) |
|  PR	         | False	 | Blood Pressure (mm Hg)        |
|  SK	         | False	 | Blood Work Result-2 (mm)      |
|  TS	         | False	 | Blood Work Result-3 (mu U/ml) |
|  M11	       | False	 | Body mass index (weight in kg/(height in m)^2|
|  BD2	       | False	 | Blood Work Result-4 (mu U/ml) |
|  Age	       | False	 | patients age (years) |
|  Insurance	 | N/A	   | If a patient holds a valid insurance card |
|  Sepssis	   | True	   | Positive: if a patient in ICU will develop sepsis and Negative: otherwise |

## Project Setup
You need to have Python 3 on your system (a Python version lower than 3.10). Then you can clone this repo and being at the repo's root:: repository_name> ... follow the steps below:

- Windows:
python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt

- Linux & MacOs:
python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt

Both long command lines have the same structure, they pipe multiple commands using the symbol, but you may manually execute them one after another.

Create Python's virtual environment that isolates the required libraries of the project to avoid conflicts;
Activate Python's virtual environment so that the Python kernel & libraries will be those of the isolated environment;
Upgrade Pip, the installed libraries/packages manager to have the up-to-date version that will work correctly;
Install the required libraries/packages listed in the requirements.txt file so that it will be allowed to import them into Python's scripts and notebooks without any issues.
NB: For macOS users, please install Xcode if you have an issue.

#### To Run FirstAPI
To run the FastAPI, paste this code to your terminal:

uvicorn main: app — reload
When you run the script and start the web server using Uvicorn, your FastAPI application becomes accessible at

http://127.0.0.1:8000
To access the documentation of your API, you can simply add “/docs” to the URL:

http://127.0.0.1:8000/docs

### Screenshot

![Sreenshot](https://user-images.githubusercontent.com/102419217/243078928-a8352c5f-afea-43b1-8bf5-c24607cf3481.gif)

# Suggestion :handshake:
It will be my pleasure that you do me a great service by recommending ways to improve in this new journey I have embarked on.

# Author :writing_hand:
+ Nathaniel Havim.
