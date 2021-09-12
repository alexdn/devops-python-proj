**Author:** Alex Danilov

This project is a result for following the "step by step" tutorial:
https://docs.google.com/document/d/1L2Foy2ueaVAO7197zMmY_gS7d7E-0vaOrIxeBMjBGqg/edit#

Running a docker container:  
Run: `docker build -t alex_danilov_phyton .`  
Run: `docker run -e AWS_ACCESS_KEY_ID="YOUR ACCESS ID" -e AWS_SECRET_ACCESS_KEY="YOUR SECRET KEY" -e AWS_DEFAULT_REGION="eu-west-1" alex_danilov_phyton`

Running without a docker:
Insure you have Python<=3.8 and pip installed.
Run: `pip install -r requirements.txt`
Run: `python src/main.py`