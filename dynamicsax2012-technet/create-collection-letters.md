---
title: Create collection letters
TOCTitle: Create collection letters
ms:assetid: 0e682e57-c057-45cd-bfdf-319a4c68dc14
ms:mtpsurl: https://technet.microsoft.com/library/Aa496410(v=AX.60)
ms:contentKeyID: 36655923
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create collection letters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create a collection letter, you must create a collection letter sequence and attach it to a customer's posting profile. For more information about collection letter sequences, see [Set up a collection letter sequence](set-up-a-collection-letter-sequence.md).

## Attach a collection letter sequence to a customer's posting profile

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Select a posting profile that is used for customers.

3.  On the **Table restrictions** FastTab, select the **Collection letter** check box.

4.  On the **Setup** FastTab, select a collection letter sequence for the account type that this customer belongs to.

## Create a collection letter

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **New collection letters**.

2.  In the **Parameters** field group, define the kind of transaction to create collection letter proposal lines for. You can also indicate the type and date of the collection letter, and whether to include all customer accounts in the periodic job, each with their own specific posting profiles, or include only customer accounts that have a particular posting profile.
    
    When you click **OK**, lines that are proposals for collection letters are automatically created in the **Print/post collection letters** form.

3.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Print/post collection letters**.

4.  Edit the proposal lines in this form, and then cancel, print, or post the proposal lines, as appropriate.
    

    > [!NOTE]
    > <P>Use the <STRONG>Collection letter journal</STRONG> form to view created, canceled, and posted collection letters. (Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>Collections</STRONG> &gt; <STRONG>Collection letter journal</STRONG>.)</P>
    > <P>(DNK) To print a collection letter together with a payment slip format, such as <STRONG>None</STRONG>, <STRONG>FIK 751</STRONG>, or <STRONG>FIK 752</STRONG>, use the <STRONG>Collection letter note</STRONG> report form. (Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Reports</STRONG> &gt; <STRONG>External</STRONG> &gt; <STRONG>Collection letter note</STRONG>.)</P>



## See also

[Set up a collection letter sequence](set-up-a-collection-letter-sequence.md)

[Control posting and printing of collection letters](control-posting-and-printing-of-collection-letters.md)

[(DNK) Set up a payment slip format for customers](dnk-set-up-a-payment-slip-format-for-customers.md)

  


