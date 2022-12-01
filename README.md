# healthcare-workshop

1. Environment setup
You need to login to Azure portal and create an Azure ML workspace. Select West or North Europe as region for your workspace. 
Here is the instruction to follow: https://docs.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources

2. Dataset that are used for the demo:  https://www.kaggle.com/sulianova/cardiovascular-disease-dataset
   Look at the description to understand the data

3. Git repository: https://github.com/JennyPopova/healthcare-workshop.git  

Start Terminal in your Compute Instance.

In the Terminal Clone repository to compute instance. Run the commad:  
_git clone https://github.com/JennyPopova/healthcare-workshop.git_


4.1 Open and run **automl-RAI-dashboard.ipynb** notebook to lear about 
   [Automl](https://learn.microsoft.com/en-us/azure/machine-learning/concept-automated-ml)
   and [Responsible AI Toolbox](https://github.com/microsoft/responsible-ai-toolbox)
   
   Find more details and documentation in **RAI-tour.ipynb** notebook

4.2 Run **custom-ml-deploy-explain.ipynb** to train custom model and deploy it as web-service together with explainer
  
5. Stop Compute Instance

Links

AzureML documentation: https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-ml

AzureML SDK: https://docs.microsoft.com/en-us/python/api/?view=azure-ml-py

AutoML: https://learn.microsoft.com/en-us/azure/machine-learning/concept-automated-ml

Responsible AI Toolbox: https://github.com/microsoft/responsible-ai-toolbox

<br />  

