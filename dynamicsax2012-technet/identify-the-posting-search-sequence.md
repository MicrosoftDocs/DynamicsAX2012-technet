---
title: Identify the posting search sequence
TOCTitle: Identify the posting search sequence
ms:assetid: e0012f69-4902-41e9-b960-977a4a3c1f10
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551302(v=AX.60)
ms:contentKeyID: 36059702
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Identify the posting search sequence 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, posting specifies the current item number, account, and sales tax code. If there is no specification for this combination, posting for the current item number and account is used, but without specification of the sales-tax code. Microsoft Dynamics AX then continues to search in the posting table until it finds a posting that matches the current transaction.

The search sequence is defined by the current settings in the customer and vendor parameters in the **Primary sales posting**, **Primary consumption transaction**, **Primary discount posting**, **Primary receipt posting**, and **Primary discount posting** fields for the current account.

If primary posting is set to **Item**, Microsoft Dynamics AX searches in the following order:

1.  **Item number**, **Account**, **Sales tax code**

2.  **Item number**, **Account**

3.  **Item number**, **Account group**, **Sales tax code**

4.  **Item number**, **Account group**

5.  **Item number**, **All accounts**, **Sales tax code**

6.  **Item number**, **All accounts**

7.  **Item group**, **Account**, **Sales tax code**

8.  **Item group**, **Account**

9.  **Item group**, **Account group**, **Sales tax code**

10. **Item group**, **Account group**

If primary posting is set to **Customer** and **Vendor**, Microsoft Dynamics AX searches in the following order:

1.  **Item number**, **Account**, **Sales tax code**

2.  **Item number**, **Account**

3.  **Item group**, **Account**, **Sales tax code**

4.  **Item group**, **Account**

5.  **All items**, **Account**, **Sales tax code**

6.  **All items**, **Account**

7.  **Item number**, **Account group**, **Sales tax code**

8.  **Item number**, **Account group**

9.  **Item group**, **Account group**, **Sales tax code**

10. **Item group**, **Account group**

This lets you set up general posting rules for all items, accounts, and sales-tax codes. You can define primary posting in customer parameters for sales, consumption, and discounts, and in vendor parameters for receipts and discounts.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

