# SendMOB_Chatbot

## Rasa Commands (Preferably using Anaconda Prompt):

### 1- Installing Rasa:
```bash
conda deactivate
conda create -n rasaenv
conda activate rasaenv
pip install rasa
rasa init
```
### 2- Communicating with Rasa:
```bash
rasa shell
```
### 3- Running Rasa Endpoints:
```bash
rasa run --cors "*" --enable-api
rasa run actions
```
### 4- Training the Model:
```bash
rasa train
```
