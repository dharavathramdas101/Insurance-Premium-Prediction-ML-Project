# Health Insurance Premium Prediction
![image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*kXLixIx8LXvLJUUc07bBeg.jpeg)

The amount of the premium for a health insurance policy depends from person to person, as many factors affect the amount of the premium for a health insurance policy. Let’s say age, a young person is very less likely to have major health problems compared to an older person. Thus, treating an older person will be expensive compared to a young one. That is why an older person is required to pay a high premium compared to a young person.

Just like age, many other factors affect the premium for a health insurance policy. Hope you now have understood what health insurance is and how the premium for a health insurance policy is determined. In the section below, I will take you through the task of health insurance premium prediction with machine learning using Python.

## Health Insurance Premium Prediction using Python
The dataset that I am using for the task of health insurance premium prediction is collected from Kaggle. It contains data about:

• Medical Charges: Total medical expense charged to the plan for the calendar year

• Age: Insurance contractor’s age, ranging from 18 to 64

• Sex: Insurance contractor’s gender, Male or Female

• BMI (Body Mass Index) = Body Mass Index, Weight(Kg)/( Height(m)² )

• Children: Number of children covered by the plan/ Number of dependants

• Region: The beneficiary’s residential area in the US. Northeast, Southeast, Northwest, Southwest

• Smoker: Whether the insurance contractor is a smoker or not, Yes or No

As mentioned, medical charges will be our dependent variable and the rest will be our independent variables.

## Tech Stack Used
    1.Python
    2.FastAPI
    3.Machine learning algorithms
    4.Docker
    5.MongoDB

## Infrastructure Required.
    1.AWS S3
    2.AWS EC2
    3.AWS ECR
    4.Git Actions
    5.Terraform

## How to run?
Before we run the project, make sure that you are having MongoDB in your local system, with Compass since we are using MongoDB for data storage. You also need AWS account to access the service like S3, ECR and EC2 instances.

## Data Collections
![image](https://user-images.githubusercontent.com/57321948/193536736-5ccff349-d1fb-486e-b920-02ad7974d089.png)

## Project Archietecture
![image](https://user-images.githubusercontent.com/57321948/193536768-ae704adc-32d9-4c6c-b234-79c152f756c5.png)

## Deployment Archietecture
![image](https://user-images.githubusercontent.com/57321948/193536973-4530fe7d-5509-4609-bfd2-cd702fc82423.png)

## Pipeline
![image](https://user-images.githubusercontent.com/102937478/216771378-4990ae29-e5c2-44df-9af4-abb1724e26b5.png)

## Home page
![image](https://github.com/dharavathramdas101/Machine-Learning-Algorithms/blob/main/insurence_data/2023-03-01%20(2).png)

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 2 - Run main.py file

```bash
python main.py
```



This is changes made in neuro lab


Git commands

If you are starting a project and you want to use git in your project
```
git init
```
Note: This is going to initalize git in your source code.


OR

You can clone exiting github repo
```
git clone <github_url>
```
Note: Clone/ Downlaod github  repo in your system


Add your changes made in file to git stagging are
```
git add file_name
```
Note: You can given file_name to add specific file or use "." to add everything to staging are


Create commits
```
git commit -m "message"
```

```
git push origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name 

To push your changes forcefully.
```
git push origin main -f
```


To pull  changes from github repo
```
git pull origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name


.env file has
```
MONGO_DB_URL="mongodb://localhost:27017"
AWS_ACCESS_KEY_ID="aagswdiquyawvdiu"
AWS_SECRET_ACCESS_KEY="sadoiuabnswodihabosdbn"
```

```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ubuntu
newgrp docker
```


```

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
AWS_ECR_LOGIN_URI=
ECR_REPOSITORY_NAME=
BUCKET_NAME=
MONGO_DB_URL=
```


```
Command to re-run the ec2 instance:

cd actions-runner/
./run.sh
```

```
GitHub Setting:

* Add Runner
* Add all the keys in the secret section


Add Runner into EC2:

√ Connected to GitHub

# Runner Registration

Enter the name of the runner group to add this runner to: [press Enter for Default] 

Enter the name of runner: [press Enter for ip-172-31-32-83] self-hosted

This runner will have the following labels: 'self-hosted', 'Linux', 'X64' 
Enter any additional labels (ex. label-1,label-2): [press Enter to skip] 

√ Runner successfully added
√ Runner connection is good
```
```
After adding the runer into github, use all the command availabe into ec2

Install Docker into EC2

curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ubuntu
newgrp docker
```
