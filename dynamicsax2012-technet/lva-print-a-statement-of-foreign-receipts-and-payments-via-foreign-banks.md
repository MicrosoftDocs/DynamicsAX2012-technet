---
title: (LVA) Print a statement of foreign receipts and payments via foreign banks
TOCTitle: (LVA) Print a statement of foreign receipts and payments via foreign banks
ms:assetid: a3665ceb-c5e3-4db8-9fb0-2b34bf738659
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721457(v=AX.60)
ms:contentKeyID: 49730235
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Latvia
---

# (LVA) Print a statement of foreign receipts and payments via foreign banks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



If a company that operates in Latvia receives payments from a foreign bank and deposits the payments into another foreign bank, or makes payments from a foreign bank, the company reports these payments on a monthly basis if their value exceeded a certain amount of Latvian Lats. You can use the **Statement of foreign payments via foreign banks** to print a report for this purpose.


> [!NOTE]
> <P>To print this monthly statement, you must create and post all bank transactions in the <STRONG>Vendor payment journal lines</STRONG> form or <STRONG>Customer payment journal lines</STRONG> form or <STRONG>General journal lines</STRONG> form. For more information, see "Create and post a journal for foreign receipts and payments".</P>



1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Select the bank account to view the transactions for. On the **Action Pane**, click **Transactions**.

2.  Select the bank, and then click **Transactions** to open the **Bank transactions** form. Enter the required details.

3.  In the **Notification to the central bank** tab, view or modify the following fields:
    
      - **Purpose text** – Modify a brief description about the purpose for which this code is used in the report, if needed.
    
      - **Central Bank Purpose Code** – View or modify the code used when reporting to the central bank.
    
      - **Correspondent country** – View or modify the country code used when reporting to the central bank.
    
      - **Payment registration number** – Modify the payment registration number assigned by the bank, if needed.

4.  Press CTRL+S or close the form.

5.  Click **Cash and bank management** \> **Inquiries** \> **Bank transactions**.

6.  Select the correspondent country and add or modify the amount criterion for bank transaction specified by Latvian Central Bank.

7.  Click **OK** to open the **Bank transactions** form to view the details on notification to the central bank, and modify them if needed.

8.  Press CTRL+S or close the form.

9.  Click **Cash and bank management** \> **Reports** \> **Transactions** \> **Foreign payments made through foreign banks**.

10. In the **Person responsible for payments** field, select or modify the code of the employee who is responsible for submitting the report.

11. In the **Month** field, select or modify the month to submit the report.

12. In the **Year** field, select or modify the year of submission for the report.
    

    > [!NOTE]
    > <P>Values in the other fields are displayed as seen in the <STRONG>Bank account transactions</STRONG> form. Click <STRONG>Select</STRONG> to open the <STRONG>Statement of foreign payments via foreign banks – Report</STRONG> form and modify these fields if necessary. You can also reset the amount criterion.</P>



13. Click **OK** to print the statement.

## See also

[(LVA) Vendor payment journal lines (modified form)](https://technet.microsoft.com/en-us/library/jj721419\(v=ax.60\))

  


