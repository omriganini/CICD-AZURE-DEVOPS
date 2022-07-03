## In this repo I will show how to build this scenario:

![project-cicd](https://user-images.githubusercontent.com/105926044/177007243-a7574611-729e-4168-b1c9-6f81862fe242.png)



## Prerequisites:
* Microsoft Azure account
* Azure Devops account
* Github account


## Guides :
* Create Azure account : https://azure.microsoft.com/en-us/free/
* Create Azure Devops account: https://azure.microsoft.com/en-us/services/devops/
* Create Github account: https://github.com/signup

## This is the Azure Devops main screen that you will work on in this project (That's what you need to see in your screen):
![1_3Y_CGyZCHPm8glku_4vTxg](https://user-images.githubusercontent.com/105926044/177007841-803b1a53-8b6d-4153-8e47-3caec8aa54d5.png)


## Create an agent :
* After you have done with all of the prerequisites you have do those steps:
* Create an agent: https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/v2-windows?view=azure-devops

* When you have an agent you can start work on the pipeline!

## CI CD pipeline :
* The Pipline have 2 big stages :
* First is the CI stage which will package our code from Github or Azure repo into an artifact
* The second stage is the CD stage which will deliver our files into the machines and deploy our app to staging and production environments!
  Here you can learn how to deploy full CI-CD pipeline via azure devops : https://docs.microsoft.com/en-us/azure/devops-project/azure-devops-project-github


# After you done with the pipeline your result should look like that:
![cicdt](https://user-images.githubusercontent.com/105926044/177008367-d0ae0e3b-0267-4bd9-8f23-62a474401adc.jpg)



# Repos I have used for my project : 
* Web app : https://github.com/omriganini/bootcamp-app
* Ansible : https://github.com/omriganini/CICD-AZURE-DEVOPS


