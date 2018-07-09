---
title: (IND) Create tax ledger posting groups for a customs tax type
TOCTitle: (IND) Create tax ledger posting groups for a customs tax type
ms:assetid: 4b783ff9-3600-47b3-beb6-760fc6b8d004
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664678(v=AX.60)
ms:contentKeyID: 49385751
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create tax ledger posting groups for a customs tax type [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must create ledger posting groups for customs tax types and define ledger accounts for customs tax components for a specific Importer-Exporter Code (IEC) number or for all IEC numbers.

You can attach the tax ledger posting groups that are set up for customs tax types to customs tax codes. The customs duty calculated in transactions are posted to the ledger accounts defined in the tax ledger posting group.

## Create and attach tax ledger posting groups

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax ledger posting groups**.

2.  Press CTRL+N to create a new line.

3.  Enter a unique name for the ledger posting group in the **Ledger posting group** field.

4.  Enter a description of the ledger posting group in the **Description** field.

5.  In the **Tax type** field, select **Customs**.

6.  Click the **Setup** tab and select the account code in the **Account code** field. The options are:
    
      - **Table** – Define the ledger accounts for a specific IEC number that is selected in the **Registration number** field.
    
      - **All** – Define the ledger accounts for all IEC numbers that are set up for Customs tax type and Company registration number type.

7.  Select the IEC number of the company in the **Registration number** field.
    

    > [!NOTE]
    > <P>If <STRONG>Table</STRONG> is selected in the <STRONG>Account code</STRONG> field, the IEC numbers set up for the Customs tax type and the Company registration number type are available in this field.</P>



8.  View the description for the IEC number in the **Description** field.

9.  Click the **Ledger accounts** tab.

10. In the **Select** field, select the type of account to attach the ledger account to the custom duty components for all the predefined accounts.
    
      - **Import duty expense account**
    
      - **Import duty payable account**
    
      - **Export duty expense account**
    
      - **Export duty payable account**
    
      - **AA receivable account**
    
      - **DFIA receivable account**
    
      - **DEPB receivable account**

11. Press CTRL+N to create a new record.

12. Select the customs tax component and the ledger account number to post the customs duty to.

## See also

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

[(IND) Create tax codes for customs](ind-create-tax-codes-for-customs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

