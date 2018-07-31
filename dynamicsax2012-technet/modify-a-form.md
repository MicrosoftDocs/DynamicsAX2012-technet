---
title: Modify a form
TOCTitle: Modify a form
ms:assetid: c5805883-74c4-4bbe-a623-c711bf1e5a2f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937978(v=AX.60)
ms:contentKeyID: 50950769
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Modify a form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX for Retail POS introduces a new way to customize forms by using the Interaction service. This enables multiple developers to customize one or more forms in one service. If there are multiple customizations, the Interaction service loads only the first customization it finds for a form. The following list of forms use this new pattern and their implementations are included in the InteractionDefaults service.

  - ExtendedLogOnForm

  - ExtendedLogOnScanForm

  - frmBarcodeSelect

  - frmDimensions

  - frmInput

  - frmPayCash

  - frmPayCurrency

  - frmPayCustomerAccount

  - frmReturnTransaction

  - LogbookForm

  - LogOnForm

  - ManagerAccessForm

  - RegisterTimeForm

  - ViewTimeClockEntriesForm

  - ProductDetailsForm

  - ProductInformationForm

## How to customize a form

You customize a form by overriding the form and then changing its functionality and its look and feel. In the following example, you customize the LogOnForm form and change the background color.

### To customize an interaction form

1.  In the folder where you installed the Retail POS SDK, open the **Microsoft Dynamics AX for Retail POS Plug-ins** folder. For more information on installing Retail POS Plug-ins, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md).

2.  Open the **Services** folder and double-click the **Services** Visual Studio solution file.

3.  Right-click the **InteractionDefaults** Visual Studio project name and rename the assembly.
    

    > [!WARNING]
    > <P>When customizing Retail POS Plug-ins, it is recommended that you give the modified assemblies new names, so that the original assemblies remain available if you need to revert back to them.</P>



4.  In this step, you override the LogOnForm form, which has a dependency on the ManagerAccessForm. Remove the other forms from the InteractionDefaults project. This enables other users to override the excluded forms. override
    
    ### To exclude unrelated forms from the project
    
    1.  Expand the **WinFormsTouch** folder and select all the forms except for the LogOnForm and ManagerAccessForm forms.
    
    2.  Right-click and select **Exclude From Project**.
    
    3.  The following diagram illustrates the **Solution Explorer** window:
        
        ![Excluding other froms InteractionDefaults folder](images/JJ937978.RemoveOtherFormsFromInteractionDefaultsFolder(en-us,AX.60).png "Excluding other froms InteractionDefaults folder")

### To change the background color

1.  Right-click the LoOnForm.cs file and select **View Code**.

2.  Add the following code to the OnLoad() method for the first line of the method.
    
        ((Form)this.BackColor = Color.DarkRed;

3.  Compile the InteractionDefaults project.

4.  Copy your new assembly to the Pos\\Services\\InteractionDefaults\\Extension folder and launch Retail POS. Your LogOnForm should now look like this:
    
    ![Log On Form with new background color](images/JJ937978.LogonFormWithNewBackgroundColor(en-us,AX.60).png "Log On Form with new background color")

  


