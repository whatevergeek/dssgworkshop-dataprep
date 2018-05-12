## Install Azure Machine Learning Workbench

Azure Machine Learning Workbench is available for Windows or macOS. 
You can install the Azure Machine Learning Workbench application on the following operating systems:
- Windows 10 or Windows Server 2016
- macOS Sierra or High Sierra

>[!WARNING]
>The installation might take around 30 minutes to complete. 

1. Download and launch the latest Workbench installer. 
   >[!IMPORTANT]
   >Download the installer fully on disk, and then run it from there. Do not run it directly from your browser's download widget.

   **On Windows:** 

   &nbsp;&nbsp;&nbsp;&nbsp;A. Download [AmlWorkbenchSetup.msi](https://aka.ms/azureml-wb-msi).  <br/>
   &nbsp;&nbsp;&nbsp;&nbsp;B. Double-click on the downloaded installer in File Explorer.

   **On macOS:** 

   &nbsp;&nbsp;&nbsp;&nbsp;A. Download [AmlWorkbench.dmg](https://aka.ms/azureml-wb-dmg). <br/>
   &nbsp;&nbsp;&nbsp;&nbsp;B. Double-click on the downloaded installer in Finder.<br/><br/>

1. Follow the on-screen instructions in your installer to completion. 

   **The installation might take around 30 minutes to complete.**  
   
   | |Installation path to Azure Machine Learning Workbench|
   |--------|------------------------------------------------|
   |Windows|C:\Users\\<user\>\AppData\Local\AmlWorkbench|
   |macOS|/Applications/Azure ML Workbench.app|

   The installer will download and set up all the necessary dependencies, such as Python, Miniconda, and other related libraries. This installation also includes the Azure cross-platform command-line tool, or Azure CLI.

1. Launch Workbench by selecting the **Launch Workbench** button on the last screen of the installer. 

   If you closed the installer:
   + On Windows, launch it using the **Machine Learning Workbench** desktop shortcut. 
   + On macOS, select **Azure ML Workbench** in Launchpad.

1. On the first screen, select **Sign in with Microsoft** to authenticate with the Azure Machine Learning Workbench. Use the same credentials you used in the Azure portal to create the [Experimentation account](/create-azure-ml-services-account.md). 

   Once you are signed in, Workbench uses the first Experimentation account it finds in your Azure subscriptions, and displays all workspaces and projects associated with that account. 

   >[!TIP]
   > You can switch to a different Experimentation account using the icon in the lower-left corner of the Workbench application window.
