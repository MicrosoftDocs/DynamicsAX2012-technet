---
title: Control posting and printing of collection letters
TOCTitle: Control posting and printing of collection letters
ms:assetid: 584c6e9d-425d-4ee8-b131-9ad3c49101eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549067(v=AX.60)
ms:contentKeyID: 36655929
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Control posting and printing of collection letters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can select options to control how collection letters are posted and printed. Before you begin, you must set up collection letters in the **Collection letter** form. (Click **Accounts receivable** \> **Setup** \> **Collections** \> **Collection letter**.)

You can select to update the collection letter code for the customer after the collection letter is printed or posted. You do this by making a selection in the **Update collection letter code** field in the **Accounts receivable parameters** form.

You can also select whether to print separate collection letters for each transaction or consolidated collection letters for each customer by using the **Collection letter** field in the **Creation of collection letter** form. (Click **Accounts receivable** \> **Periodic** \> **Collections** \> **New collection letters**.)

## Specify when collection letters are posted

Suppose your legal entity has three different letters that you can send to a customer, and you selected **Printout** in the **Update collection letter code** field in the **Accounts receivable parameters** form. After you print the first collection letter, the second collection letter will be printed the next time that you print a collection letter for the same customer.

If you selected **Posting** in the **Update collection letter code** field, instead, after you post the first collection letter, the second collection letter will be printed the next time that you print a collection letter for the same customer.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Collections** area, in the **Update collection letter code** list, select **Posting** or **Printout**.
    
      - **Posting** – The collection journal is updated to the next step when a collection letter is posted.
    

    > [!NOTE]
    > <P>If you select this option and you also select <STRONG>All</STRONG> in the <STRONG>Collection letter</STRONG> field in the <STRONG>Creation of collection letter</STRONG> form, only one collection letter is created and posted for the customer. The collection letter includes all overdue invoices.</P>

    
      - **Printout** – The collection journal is updated to the next step when you print a collection letter.
    

    > [!NOTE]
    > <P>If you select this option and you also select <STRONG>All</STRONG> in the <STRONG>Collection letter</STRONG> field in the <STRONG>Creation of collection letter</STRONG> form, a collection letter is printed for each date that the customer has overdue invoices. Each collection letter can include several invoices.</P>

    
    For more information, see the description of the **Update collection letter code** field in [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Specify how collection letters are printed

You can select whether to print separate collection letters for each transaction or consolidated collection letters for each customer.

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **New collection letters**.

2.  Select a collection letter option in the **Collection letter** field.
    
      - Select **Collection per customer** to print only one collection letter for the customer, regardless of the number of collection letter codes that apply to the customer. The text in the letter is displayed from the highest collection letter code that applies to the open transactions of the customer. The value 1 is the lowest collection letter code.
    
      - Select **All** to print all collection letters for the customer.
    
      - Select any of the other options to print the corresponding collection letter.
    
    You can set up collection letter codes in the **Collection letter** form. For more information, see [Collection letter (form)](https://technet.microsoft.com/en-us/library/aa620428\(v=ax.60\)).

## See also

[Set up a collection letter sequence](set-up-a-collection-letter-sequence.md)

[Create collection letters](create-collection-letters.md)

  


