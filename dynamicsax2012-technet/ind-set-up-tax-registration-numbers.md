---
title: (IND) Set up tax registration numbers
TOCTitle: (IND) Set up tax registration numbers
ms:assetid: 9338fdc9-fa9c-4b89-b576-bc8bad1dd848
ms:mtpsurl: https://technet.microsoft.com/library/JJ678041(v=AX.60)
ms:contentKeyID: 49386000
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up tax registration numbers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Enterprise tax registration numbers** form to set up tax registration numbers for direct and indirect taxes. You can set up direct tax registration numbers for companies, vendors, and customers.

You can set up the following tax registration numbers for indirect taxes:

  - **VAT**

  - **India sales tax**

  - **Excise**

  - **Service tax** **(STC)**

  - **Customs**

## Set up tax registration numbers

### To set up a tax registration number for an indirect tax

1.  Click **General ledger** \> **Setup** \> **Enterprise tax registration numbers**.

2.  In the **Select tax** field, select **Indirect**.

3.  In the **Tax type** field, select the type of indirect tax to set up a registration number for.

4.  In the **Registration number type** field, select **Company**, **Customers**, or **Vendors** to indicate who the tax registration number is for.

5.  Enter the registration number and a description for the tax.

6.  Select the **Shared** check box if the tax registration number should be available to all legal entities.

7.  If you selected **Excise** in step 3 and **Company** in step 4, select a number sequence code for each reference.

### To set up a tax registration number for a direct tax

1.  Click **General ledger** \> **Setup** \> **Enterprise tax registration numbers**.

2.  In the **Select tax** field, select **Direct**.

3.  In the **Registration number type** field, select **Company**, **Customers**, or **Vendors** to indicate who the tax registration number is for.

4.  Click **New**.

5.  Enter the registration number and description for the direct tax.

6.  Select the **Shared** check box if the tax registration number should be available to all legal entities.

7.  On the **General** FastTab, enter the following information for Tax Deducted at Source (TDS) and Tax Collected at Source (TCS):
    
      - **Circle number** – Enter the circle numbers for the TDS and TCS authorities.
    
      - **Ward number** – Enter the ward numbers for the TDS and TCS authorities.
    
      - **Assessing officer** – Enter the names of the assessing officers for the TDS and TCS authorities.

## See also

[(IND) Key tasks: Tax information for legal entities](ind-key-tasks-tax-information-for-legal-entities.md)

[(IND) Claim status (form)](https://technet.microsoft.com/library/jj710913\(v=ax.60\))

  


