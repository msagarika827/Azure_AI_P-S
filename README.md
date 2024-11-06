Overview
This repository contains lab files and code examples for getting started with Azure AI Services. The exercises will guide you through creating Azure AI resources and using them to perform language detection through both REST API and SDK methods.

Prerequisites
Azure Subscription: You need an Azure subscription to create resources.
Visual Studio Code: Install Visual Studio Code for code editing.
Python or C#: Familiarity with either Python or C# is required for the coding exercises.

Getting Started

Clone the Repository
1-Open Visual Studio Code.
2-Open the command palette (Shift + Ctrl + P).
3-Run the command Git: Clone and use the following URL:

https://github.com/MicrosoftLearning/mslearn-ai-services
4-Open the cloned folder in Visual Studio Code.

Sign In to Azure
1-Log in to Windows using the student account:
Username:
Password: 
2-Open the Azure portal at https://portal.azure.com and sign in with your Azure account.

Create Azure AI Services Resource
1-In the Azure portal, search for Azure AI Services.
2-Create a new multi-service account with the following settings:
Subscription: Your Azure subscription
Resource group: ******
Region: Choose any available region
Name: Enter a unique name
Pricing tier:*****
3-Complete the resource creation and note down the Keys and Endpoint for later use.

Using the Code
REST Client
Navigate to the rest-client folder in either C# or Python.

Update the configuration file:

Python: .env
C#: appsettings.json
Set AI_SERVICE_ENDPOINT and AI_SERVICE_KEY with your Azure AI Services resource details.
Run the client application:

For Python:
bash

Verify

Open In Editor
Edit
Copy code
pip install python-dotenv
python rest-client.py
For C#:
bash

Verify

Open In Editor
Edit
Copy code
dotnet run
Enter text to detect the language. Type "quit" to exit.

SDK Client
Navigate to the sdk-client folder in either C# or Python.

Update the configuration file as described above.

Install the SDK package:

For Python:
bash

Verify

Open In Editor
Edit
Copy code
pip install azure-ai-textanalytics==5.3.0
For C#:
bash

Verify

Open In Editor
Edit
Copy code
dotnet add package Azure.AI.TextAnalytics --version 5.3.0
Run the SDK client application:

For Python:
bash

Verify

Open In Editor
Edit
Copy code
python sdk-client.py
For C#:
bash

Verify

Open In Editor
Edit
Copy code
dotnet run
Enter text to detect the language. Type "quit" to exit.

Clean Up Resources
To avoid incurring charges, delete the Azure resources created during this lab:

Go to the Azure portal.
Search for the resources created during the lab.
Select and delete the resources or the entire resource group.
Conclusion
Congratulations! You have successfully completed the Azure AI Services lab exercises. You should now have a better understanding of how to provision and interact with Azure AI Services.

Additional Resources
For more information about Azure AI Services, refer to the official Azure AI Services documentation.

