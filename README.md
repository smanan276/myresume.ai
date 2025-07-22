# resume-analysis.ai

Resume Analysis...

### Steps for creating the project

- Create the Virtual Environment using ``python - m venv .venv``
- Activate the Virtual Environment using ``source .venv/Scripts/activate``
- Create the .env file to store the API key
- Create the requirements.txt file and add the libraries for installation using ``pip install - r requirements.txt``
### Project Synopsis
* We want to create an Application that will analyse the resume of the candidate using Gen AI model with the job desc and provide insights such as :-
- ATS scores 
- probability of getting hired
- keyword analysis
- SWOT Analysis
- Suggestion for Overall Improvements

## Architecture
* app.py : Front end creation and output of the Genai Model.
It will have the feature of capturing information such as Resume and JD
* Information we are capturing is ``Resume.pdf`` and    `` job_des``.
* Pdf.py that will process the information in pdf and thats why we have installed ``pypdf ``
* analysis.py that will triangulate the pdf information and the JD and will provide insights and next step.
