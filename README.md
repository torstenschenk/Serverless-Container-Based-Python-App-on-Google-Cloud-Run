[![Serverless Container Python App](https://static.codingforentrepreneurs.com/media/projects/serverless-container-python-app/images/share/Serverless_Container_on_GCP_-_Share.jpg)](https://www.codingforentrepreneurs.com/projects/serverless-container-python-app/)

# Serverless Container Python App

Serverless enables you to focus on code, not infrastructure. Deploy a Docker Container to Cloud Run using this series. Cloud Run is a service by the Google Cloud Platform.

## Resources:
- Course [here](https://www.codingforentrepreneurs.com/projects/serverless-container-python-app/).
- Install Gcloud CLI Blog post [here](https://www.codingforentrepreneurs.com/blog/google-cloud-cli-and-sdk-setup/)



This project has been updated. To view the 2020 version of the code go [here](https://github.com/codingforentrepreneurs/Serverless-Container-Based-Python-App-on-Google-Cloud-Run-2020).

## Environment

Set up your Environment

For **`macOS`** :
```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyterlab
```

For **`WindowsOS`** : 

open `PowerShell` CLI as an administrator :

```Bash
pyenv local 3.11.3
python -m venv .venv
# python3.11 -m venv .venv
.venv\bin\activate
#.venv\Script\Activate.ps1
python -m pip install --upgrade pip
pip install jupyterlab
```

open `Git-Bash` CLI as an administrator :
```
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
python -m pip install --upgrade pip
pip install jupyterlab
```
*Note :*
If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

```Bash
# python.exe -m pip install --upgrade pip

pip install --upgrade pip
pip install -r src/requirements.txt
```
