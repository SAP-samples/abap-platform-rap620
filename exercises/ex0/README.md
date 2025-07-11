# TOC
[Home](../../readme.md#exercises)  
### ABAP Development Tools (ADT)
In order to participate in this hands-on session, you MUST have installed the latest version of Eclipse and the latest version of the ABAP Development Tools (ADT) in Eclipse. Please check the following two short documents how to do this if you have not already done it:     
   - [Install the ABAP Development Tools (ADT)](https://github.com/SAP-samples/abap-platform-rap-workshops/blob/main/requirements_rap_workshops.md#3-install-the-abap-development-tools-adt)  
   - [Adapt the Web Browser settings in your ADT installation](https://github.com/SAP-samples/abap-platform-rap-workshops/blob/main/requirements_rap_workshops.md#4-adapt-the-web-browser-settings-in-your-adt-installation)  

### SAP BTP Trial Account

You also need a user on an SAP BTP ABAP Environment system. For this tutorial you can use the free trial offering of SAP Business Technology Platform (BTP) 

- You have created a trial account on SAP Cloud Platform: [Get a Free Trial Account on SAP BTP](https://developers.sap.com/tutorials/hcp-create-trial-account.html).
- You have prepared your ABAP Trial which can be easily be done via the [SAP BTP cockpit](https://cockpit.hanatrial.ondemand.com) in just 3 steps.
                                                                                           
  - Click on **Go To Your Trial Account**.
  ![Enter Trial](images/intro_0000.png)
  - Click on **Boosters** in the menu on the left hand side
  - Choose the tile **Prepare an Account for ABAP Trial** and follow the wizard
  ![Start booster](images/intro_0010.png)

  For a detailed step-by-step description check out our tutorial: [OCreate an SAP BTP ABAP Environment Trial User](https://developers.sap.com/tutorials/abap-environment-trial-onboarding..html).

> **Note for participants of SAP events:** You might recieve seperate logon information from the SAP team during the event to access a dedicated system.   

### Connect ADT to the SAP BTP trial ABAP Environment system

   1. In ADT, from the menue select **New** > **ABAP Cloud Project**.   

      ![ABAP Cloud Project](images/connect_adt_0000.png) 

      This will open the *New ABAP Cloud Project* wizard.  
 
   2. Here you have to enter the **ABAP Service Instance URL** you obtained when running the booster. 

      Press **Next>**   
 
      ![ABAP Cloud Project](images/connect_adt_0005.png) 
 
      
      > As a result a new ABAP cloud project will be opened.

 
   2. In the **Logon to the SAP Cloud System**  press the button **Open Logon Page in Browser**. This will open the default browser that is configured in ADT. If needed enter your credentials to log on to the SAP BTP platform. When you have just logged on to create the trial ABAP Environment instance you will be automatically authenticated.  
 
 
        ![ABAP Cloud Project](images/connect_adt_0030.png)  
 
 
   6. In the **Service Instance Connection** screen just press **Finish**. 
 
 
        ![ABAP Cloud Project](images/connect_adt_0040.png)  
 
