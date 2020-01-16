---
title: Set up system parameters
TOCTitle: Set up system parameters
ms:assetid: bb9fc1ee-5f33-4094-9a8f-20eadd15ebd8
ms:mtpsurl: https://technet.microsoft.com/library/Gg731914(v=AX.60)
ms:contentKeyID: 35132840
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Menu_Items.Display.BISetupExchangeRates
- Menu_Items.Display.SystemParameters
---

# Set up system parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following procedures to maintain parameters that apply to all legal entities that are set up in Microsoft Dynamics AX.

These procedures use the **System parameters** form. This form can also be opened from the initialization checklist or partition initialization checklist. Depending on your version of the program, do one of the following:

  - In Microsoft Dynamics AX 2012: Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**. Click **Initialize system** \> **Set up system parameters**.

  - In Microsoft Dynamics AX 2012 R2: Click **System administration** \> **Setup** \> **Checklists** \> **Partition initialization checklist**. Click **Partition initialization checklist** \> **Set up system parameters**.

If you open the form from the initialization checklist or the partition initialization checklist, some of the parameters that are listed here might not be available. You can set up the remaining parameters at any time after you have completed the initialization or partition initialization.

## Set up general system parameters

1.  Click **System administration** \> **Setup** \> **System parameters**.

2.  Click **General**, and then select options for the general system parameters:
    
      - **System language** – Select the default language to use for text translations.
    
      - **Increment** – Enter the increment to use when new line numbers are assigned to purchase order lines. This increment is used for all purchase order lines. Line increments are applied for purchase orders only.
    
      - **System currency** – Select the currency to use. You can define a default currency for each ledger that you set up in the **Ledger** form.
        
        This currency is used only to consolidate amounts in General ledger that have been posted in different currencies from various legal entities.
        

        > [!NOTE]
        > <P>Currencies will not be available until you set up General ledger parameters for your legal entity.</P>

    
      - **System exchange rate type** – Select the exchange rate to use. Define a default exchange rate type for each legal entity in the **Ledger** form.
    
      - **Chart of accounts delimiter** – Select the symbol to use as the separator between financial dimensions.

## Set up parameters for alerts

1.  Click **System administration** \> **Setup** \> **System parameters**.

2.  Click **Alerts**, and then select the options for alerts:
    
      - **Batch processing window (days)** – Enter a number of days. The number of days that you enter will be added to the time limit that is set up for alerts.
    
      - **E-mail ID** – Select the ID that corresponds to the email template that you created for alert notifications.
    
      - **Drill-down target** – Enter the value that corresponds to the database where the event occurred. The database value is required if you want a user to be able to drill down to the event from the alert notification.

## Set up the parameter for file storage

1.  Click **System administration** \> **Setup** \> **System parameters**.

2.  Click **File store**, and then select the option for file storage:
    
      - **Directory** – Select a shared network location for file storage. For detailed information about the purposes of the file storage location, see [Set up general system parameters (form)](https://technet.microsoft.com/library/hh209515\(v=ax.60\)).

## Set up number sequences

1.  Click **System administration** \> **Setup** \> **System parameters**.

2.  Click **Number sequences**, and then select the options for number sequences:
    
      - **Reference** – Select the number sequence for the purposes of generating workflow configuration ID numbers, workflow instance ID numbers, and alert rule ID numbers.
    
      - **Number sequence code** – Select a number sequence code for the corresponding ID number.

## See also

[About alert batch execution](about-alert-batch-execution.md)

[Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md)

[About drilling down from an alert email message](about-drilling-down-from-an-alert-email-message.md)

  


