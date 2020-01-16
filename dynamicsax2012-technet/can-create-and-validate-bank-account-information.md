---
title: (CAN) Create and validate bank account information
TOCTitle: (CAN) Create and validate bank account information
ms:assetid: 8964262f-1a1f-4710-987c-f1e0093fb023
ms:mtpsurl: https://technet.microsoft.com/library/Hh209343(v=AX.60)
ms:contentKeyID: 36058460
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Canada
- validate bank account
audience: Application User
ms.search.region: Canada
---

# (CAN) Create and validate bank account information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up a bank account and bank group to submit payments to vendors or receive payments from customers, the bank account information is validated against specific validation criteria mandated by the Canadian banking system. In the **Application user Help** form, on the **Address** tab, select **CAN** in the **Country/region** field so that the validation can be performed. The bank account number, routing number type, and routing number are validated. Use the following procedures to set up bank accounts and bank groups to validate your bank account information.

## Set up a bank group to validate bank account information

Use the **Bank groups** form to set up and validate a bank account.

1.  Click **Cash and bank management** \> **Setup** \> **Bank groups**.

2.  Press CTRL+N to create a bank group.

3.  In the **Routing number** field, enter the bank’s unique registration number. This nine-character string is used with the account number to identify a specific bank account.
    
    The Canadian Payments Association, which regulates the routing number format, allows the following formats: XXXXX-YYY (for regular transactions) and 0YYYXXXXX (for electronic fund transfers), where YYY is the institution number and XXXXX is the bank branch.

4.  Click the **General** FastTab.

5.  In the **Routing number type** field, enter **cc** as the routing number type for the account.

6.  Close the form to save your changes.

## Set up bank accounts to validate bank account information

Use the **Bank accounts** form, the **Vendor bank accounts** form, and the **Customer bank accounts** form to set up and validate bank accounts in compliance with Canadian bank regulations.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Click **Set up** \> **Bank accounts** to open the **Customer bank accounts** form.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Click **Setup** \> **Bank accounts** to open the **Vendor bank accounts** form.

2.  Click **Bank account**.

3.  Click the **General** tab.

4.  In the **Routing number type** field, enter **cc** as the routing number type.

5.  In the **Routing number** field, enter the bank’s unique registration number. This nine-character string is used with the account number to identify a specific bank account.
    
    The Canadian Payments Association, which regulates the routing number format, allows the following formats: XXXXX-YYY (for regular transactions) and 0YYYXXXXX (for electronic fund transfers), where YYY is the institution number and XXXXX is the bank branch.

6.  In the **Bank account number** field, enter the unique bank account number, which is a numeric string containing up to 12 digits.

7.  Close the form to save your changes.

## See also

[Bank groups (form)](https://technet.microsoft.com/library/aa571457\(v=ax.60\))

[Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\))

[Customer bank accounts (form)](https://technet.microsoft.com/library/aa575695\(v=ax.60\))

  


