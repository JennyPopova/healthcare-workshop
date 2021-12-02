# healthcare-workshop

1. Environment setup
You need to login to Azure portal and create an Azure ML workspace. Select West or North Europe as region for your workspace. 
Here is the instruction to follow: https://docs.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources

2. Git repository: https://github.com/JennyPopova/healthcare-workshop.git  

Start Terminal in your Compute Instance
In the Terminal Clone repository to compute instance:  _git clone https://github.com/JennyPopova/healthcare-workshop.git ./Users/healthcare-workshop__

3. Dataset
Download Dataset:  https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

Register Tabular dataset in AzureML with a name 'cardio_dataset' from local file

4. Run automl-explain-model-SHAP.ipynb, explore Experiment section in Azure ML
  Run custom-ml-deploy-explain.ipynb, explore Experiment section in Azure ML
  
5. Stop Compute Instance

Links

AzureML documentation: https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml

Data Labeling: https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-labeling

AzureML SDK: https://docs.microsoft.com/en-us/python/api/?view=azure-ml-py

<br />  

