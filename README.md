# 🧪 Auto_News_Research
Keeping up with the latest news will no longer be problem any more

****
Description: 
Simplify your news research with precision! Access curated financial (or any other) news tailored to your interests and receive automatic analyses explaining market reactions. Save time and stay informed effortlessly.
*****

## **🌍 Automation_Process**
1. Prompt GPT 
2. Get stock movers
3. get stock news
4. Add news to Airtable

*****
![](images/Capture.PNG)

## 🌐 How to run?
### STEPS:

Clone the repository

```bash
https://github.com/AleemAhmedKhan/Auto_News_Research.git    
```
### 💽  STEP 01- Create a conda environment after opening the repository
    
```bash
conda create -n news python=3.8 -y
```

```bash
conda activate news
```


###  🔍 STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


## 📡 CICD-Deployment-with-Github-Actions

## 🛠 Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 
