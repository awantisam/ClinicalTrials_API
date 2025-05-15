# ClinicalTrials_API
API to summarize and visualize data from ClinicalTrials.gov


# Installation
To successfully install and run this application, you would need Docker. Run the following code in the terminal:

git clone https://github.com/awantisam/ClinicalTrials_API.git
cd ClinicalTrials_API
docker compose up --build
Then access the application via the following address in your browser: http://localhost:8000/
alt text

# Usage
This application can be used to view and summarize a clinical trial study based on its NCT ID or number. Two features are currently supported:

View data on a clinical trial study: supply an NCT ID to the view port. E.g.: http://localhost:8000/view/NCT00841061
![image](https://github.com/user-attachments/assets/45e9b064-559c-4083-9f29-ddee90513703)


Summarize data on a clinical trial study: supply an NCT ID to the summarize port. E.g.: http://localhost:8000/summarize/NCT00841061
<img width="803" alt="image" src="https://github.com/user-attachments/assets/f43b5267-137d-4eba-8c94-3f7e3dd6a554" />


Documentation
The API documentation can be found here: http://localhost:8000/docs

Repository structure:
ClinicalTrials_API
└───images             [example images]
|   Dockerfile         [Docker build file]
|   compose.yml        [Docker compose configuration]
|   main.py            [Python script for application]
|   requirements.txt   [Python package dependencies]
