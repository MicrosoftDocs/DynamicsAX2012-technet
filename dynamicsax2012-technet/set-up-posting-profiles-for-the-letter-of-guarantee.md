---
title: Set up posting profiles for the letter of guarantee
TOCTitle: Set up posting profiles for the letter of guarantee
ms:assetid: b37d27cc-4be8-4bd5-94b6-7c7e613f9bf3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242749(v=AX.60)
ms:contentKeyID: 36059068
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Posting profiles for the letter of guarantee
- Set up posting profiles for the letter of guarantee
---

# Set up posting profiles for the letter of guarantee 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Bank documents posting profile** form to set up a posting profile for a letter of guarantee transaction.

1.  Click **Cash and bank management** \> **Setup** \> **Bank documents** \> **Bank documents posting profile**.

2.  Press CTRL+N to create a new bank document posting profile.

3.  In the **Account code** field, select one of the following options:
    
      - **Table** – Assign all accounts to a bank facility type.
    
      - **Group** – Assign a specific account to a bank facility group.
    
      - **All** – Do not assign any account to a bank facility type or group.

4.  If you selected **Table** or **Group**, select the facility type in the **Account/Group number** field. If you selected **All**, the **Account/Group number** field is not available.

5.  In the **Settle account** field, select the main account for settlement.

6.  In the **Charges account** field, select the account for expense transactions.

7.  In the **Margin account** field, select the account for the margin transaction.

8.  In the **Liquidation account** field, select the liquidation account for the letter of guarantee transaction. This field is available only if you have selected the **Enable letter of guarantee** check box in the **Cash and bank management parameters** form.

9.  Close the form to save your changes.

## See also

[Letter of guarantee (form)](https://technet.microsoft.com/en-us/library/hh227662\(v=ax.60\))

[Set up letter of guarantee cancellation reasons and purpose code types](set-up-letter-of-guarantee-cancellation-reasons-and-purpose-code-types.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

