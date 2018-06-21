---
title: (RUS) Set up a deferrals model
TOCTitle: (RUS) Set up a deferrals model
ms:assetid: 165057d0-5921-4004-b0d0-7dd41af7157c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711427(v=AX.60)
ms:contentKeyID: 49387245
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- deferrals
---

# (RUS) Set up a deferrals model [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Deferrals models** form to specify the ledger account that is used to post write-off transactions. For more information, see [(RUS) Deferrals models (form)](https://technet.microsoft.com/en-us/library/jj678655\(v=ax.60\)).

You can specify the write-off amount for each interval for a deferrals model. Each deferrals model is linked to a deferral ID. When you generate a write-off transaction in the deferral journal for a deferral ID, the write-off amounts that are specified for the associated deferrals model are created on the journal lines. You can then post the journal.

1.  Click **General ledger** \> **Common** \> **Deferrals**. Click **Deferrals models**.

2.  Create a new deferrals model.

3.  In the **Model number** and **Deferrals group** fields, select the deferrals model and deferrals group to associate with the deferral. The write-off method and the starting date for the deferrals write-off are displayed.

4.  In the **Deferrals sum** field, enter the value of the deferral.

5.  Click the **General** tab, and then, in the **Ledger account** field, select the ledger account to use to post the write-off transaction.
    

    > [!NOTE]
    > <P>If you do not specify a ledger account in this field, the ledger account that is specified in the <STRONG>Main account</STRONG> field for the <STRONG>Receipt</STRONG> option in the <STRONG>Deferrals posting profiles</STRONG> form is used to post the transaction.</P>



6.  Click **Writing off sum** to open the **Deferrals sum for writing off calculation** form.

7.  Create a new line to enter the write-off amount. The **Interval number** field displays the interval number that is used to write off the deferral amount.

8.  In the **Writing off sum** field, enter the write-off amount for the interval. The **Deferrals sum** field displays the total amount that is written-off. This amount is the sum of the amounts that are entered in the **Writing off sum** field.

9.  Close the form.

10. In the **Deferrals models** form, click the **Financial dimensions** tab, and then select the value of the financial dimensions.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

