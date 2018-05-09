---
title: (IND) Set up EXIM ports
TOCTitle: (IND) Set up EXIM ports
ms:assetid: d96db641-4d7c-439e-b034-f00e24ae6066
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664931(v=AX.60)
ms:contentKeyID: 49386260
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EXIM
- EXIM ports
- set up EXIM
---

# (IND) Set up EXIM ports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Set up the export and import (EXIM) port authorities that you reference in export and import transactions when you apply for Advanced Authorization (AA), Duty Free Import Authorization (DFIA), Export Promotion Capital Goods (EPCG), or Duty Drawback (DBK) incentives.

  - Before you set up the EXIM port authority data for DBK incentives, you must create a customer account and customer bank account for the port authority. For more information about how to set up a customer account and customer bank account, see [Create a customer record](create-a-customer-record.md) and [Set up a bank account for a customer account](set-up-a-bank-account-for-a-customer-account.md).

  - To access the **EXIM ports** form, you must first activate incentive schemes. In the **General ledger parameters** form, in the **Sales tax** area, on the **General** FastTab, select the **Activate incentive schemes** check box.

### Set up EXIM ports

1.  Click **General ledger** \> **Setup** \> **EXIM** \> **EXIM ports**.

2.  In the **EXIM ports** form, click **New** to create a new EXIM port.

3.  On the **General** FastTab, in the **Port ID** field, enter the name of the port. In the **Description** field, enter a description of the port.

4.  In the **Bank account** field, select the company bank account that is registered with the port authority.
    
    For more information about how to set up a bank account, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

5.  In the **Registration number** field, enter the registration number that the port authority issued for the bank account.

6.  In the **Customer account** field, select the authority customer account for the port.

7.  On the **Address** FastTab, click **New** to enter a new address for the port.

8.  In the **New address** form, enter the address details for the port.

## See also

[(IND) EXIM ports (form)](https://technet.microsoft.com/en-us/library/jj677922\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

