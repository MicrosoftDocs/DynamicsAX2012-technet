---
title: (EEUR) Configure reason code requirements for credit notes
TOCTitle: (EEUR) Configure reason code requirements for credit notes
ms:assetid: 46e58a1f-b285-4745-a22b-92048dddd8f4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853388(v=AX.60)
ms:contentKeyID: 50396757
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Configure reason code requirements for credit notes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Reason codes help explain why some types of transaction were entered or why some field values were changed. For example, you can create reason code to use with write-down adjustments or modifications in the **Sales value** field in Fixed assets.

You can use the **Financial reasons** form in Organization administration to create the same codes to use across various modules, or you can set up reason codes for other modules in the corresponding forms for those modules. In Organization administration, you can assign a reason code to any of the modules, but in the other modules, you can assign the reason code only to that module. For example, if you open the **Vendor reasons** form in Accounts payable, the account type is automatically set to **Vendor**, and the reason codes that you create can be used only with vendor transactions.

Reasons can be used along with descriptions, and you can sort and analyze transaction history by reason code. Also, auditors can use reason codes to verify the purpose for transactions or field changes. Depending on how your organization uses reason codes, you might want to provide guidelines about when to use each reason code.

1.  Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

5.  Click **Close**.

6.  To require reasons for changes in Accounts receivable, select the appropriate check boxes on the **Reason code requirements** FastTab in the **General** area of the **Accounts receivable parameters** form. (Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.)
    

    > [!NOTE]
    > <P>To require reasons for credit notes, select the <STRONG>Require reasons for credit notes</STRONG> check box on the <STRONG>Accounts receivable parameters</STRONG> form.</P>



## See also

[Set up reason codes for financial modules](set-up-reason-codes-for-financial-modules.md)

  


