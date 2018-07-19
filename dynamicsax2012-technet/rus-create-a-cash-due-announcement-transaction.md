---
title: (RUS) Create a cash due announcement transaction
TOCTitle: (RUS) Create a cash due announcement transaction
ms:assetid: c9c8afe9-954b-4262-871f-503cda54ef30
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711596(v=AX.60)
ms:contentKeyID: 49387920
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a cash due announcement transaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The cash due announcement allows you to export the cash due announcement report (unified report 0402001.xlt) to the registered bank when you update the journal.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Journals** \> **Slip journal**. Select a slip journal, and then, on the menu bar, click**Lines**

2.  Press CTRL+N to create a new journal line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Create and validate a journal and journal lines" in the Applications and Business Processes Help.</P>



3.  In the **Offset account type** field, select **Bank**.

4.  In the **Offset account** field, select the offset account for the transaction.

5.  Click the **Payment** tab.

6.  In the **Bank transaction type** field, select a bank transaction type code that allows creation of a cash due announcement for bank transactions.
    

    > [!NOTE]
    > <P>The cash due announcement number is automatically generated and is displayed in the <STRONG>Cash due announcement</STRONG> field.</P>



7.  Click the **Cash order** tab.
    

    > [!NOTE]
    > <P>The cash due announcement number and the date on which the cash due announcement was created are displayed in the <STRONG>Document</STRONG> and <STRONG>Document date</STRONG> fields.</P>



8.  Press CTRL+S or close the form.

## See also

[(RUS) Set up a cash due announcement](rus-set-up-a-cash-due-announcement.md)

  


