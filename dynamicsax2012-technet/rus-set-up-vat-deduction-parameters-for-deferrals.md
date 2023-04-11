---
title: (RUS) Set up VAT deduction parameters for deferrals
TOCTitle: (RUS) Set up VAT deduction parameters for deferrals
ms:assetid: 65e0d79e-3782-49ff-8b86-334e593a61a4
ms:mtpsurl: https://technet.microsoft.com/library/JJ665459(v=AX.60)
ms:contentKeyID: 49387546
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up VAT deduction parameters for deferrals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

VAT deductions are calculated in proportion to deferral amounts that have been written off. For example, for the purchase of service items, operational equipment, or other commodities. At the end of each tax reporting period, you must mark the VAT that was received during that period as closed using incoming VAT processing in the purchase book. When you process incoming VAT to write off deferrals, you can verify the calculated blocked and unblocked facture VAT amounts, and then record the transactions in the purchase book. If you have not yet closed the purchase book for a period, you can reverse the transaction in the general journal to cancel the deferral amount that was written off. Use the following procedures to set up VAT deduction parameters for deferrals.

## Prerequisites for processing incoming VAT for deferrals

Before you set up VAT deduction parameters for deferrals, and to process incoming VAT for deferral amounts, complete the following tasks:

  - Set up sales tax settlement periods and sales tax codes. For more information, see [Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\)).

  - Set up the sales tax groups and item sales tax groups. For more information, see [Sales tax groups (form)](https://technet.microsoft.com/library/aa498345\(v=ax.60\)) and [Item sales tax groups (form)](https://technet.microsoft.com/library/aa615960\(v=ax.60\)).

  - Set up the expense and income codes.

You must also complete the following tasks to calculate VAT deduction for deferrals:

  - Set up writing off methods and posting profiles for deferrals. For more information, see [(RUS) Writing off methods (form)](https://technet.microsoft.com/library/jj711659\(v=ax.60\)) and [(RUS) Deferrals posting profiles (form)](https://technet.microsoft.com/library/jj665468\(v=ax.60\)).

  - Create deferral models and specify write-off method details. For more information, see [(RUS) Deferrals models (form)](https://technet.microsoft.com/library/jj678655\(v=ax.60\)).

  - Generate a deferrals write-off ratio. For more information, see [(RUS) Generate a deferrals write-off ratio](rus-generate-a-deferrals-write-off-ratio.md).

  - Set up purchase book and VAT offset method parameters for incoming VAT processing in the **Accounts payable parameters** form and the **General ledger parameters** form.

  - Set up a deferrals group.

  - Set up counters for calculation sequences with quantity and price as the line types.

## Set up accounts payable parameters for deferrals

Use the **Accounts payable parameters** form to set up the grouping parameter for deferrals. For more information, see [Accounts payable parameters (form)](https://technet.microsoft.com/library/aa596348\(v=ax.60\)).

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click the **Ledger and sales tax** link.

3.  Select the **Group by lot ID** check box to group the factures by lot identification when VAT is processed.

## Set up the VAT offset method for deferrals

Use the **General ledger parameters** form to specify the VAT deduction method for deferrals.


> [!NOTE]
> <P>If you set the <STRONG>VAT offset method for deferrals</STRONG> field in the <STRONG>General ledger parameters</STRONG> form to <STRONG>Proportionate</STRONG>, the VAT deduction is calculated in proportion to the deferral amount that was written off.</P>



1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Deferrals** link, and in the **VAT offset method for deferrals** field, select **Proportionate** as the method for VAT deduction deferrals.
    

    > [!NOTE]
    > <P>Select <STRONG>Standard</STRONG> as the VAT deduction deferral method to apply general incoming VAT processing to the facture.</P>



3.  Click the **Number sequences** link, and then select the number sequence codes for the **Journal**, **Fixed asset number**, **Facture**, and **Deferral ID** references.

## Set up a deferrals group

Use the **Deferrals groups** form to create groups for deferrals and specify the VAT deduction method for each group. Before creating a deferrals group, you must create write-off methods and deferrals models. For more information, see [(RUS) Writing off methods (form)](https://technet.microsoft.com/library/jj711659\(v=ax.60\)) and [(RUS) Deferrals models (form)](https://technet.microsoft.com/library/jj678655\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Deferrals groups**.

2.  Press CTRL+N to create a new deferrals group.

3.  In the **Deferrals group** field, enter a unique code for the deferrals group.

4.  In the **Name** field, enter a description of the deferrals group.

5.  In the **Model number** field, select the model number for the deferrals.

6.  Click the **General** FastTab and verify that **Proportionate** is selected in the **VAT offset method for deferrals** field.

## Set up counters

Use the **Counter setup** form to set the calculation sequence for deferrals to **Quantity** multiplied by **Price**. For more information, see [(RUS) Set up calculation sequences, counters, and deferred expense write-off factors](rus-set-up-calculation-sequences-counters-and-deferred-expense-write-off-factors.md).

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Sequence of calculation**.

2.  Press CTRL+N to create a new sequence.

3.  In the **Sequence** field, view or modify the calculation sequence code. Enter a description of the sequence in the **Description** field.

4.  In the **Channel** and **Channel reference** fields, select the deferral and select the register or deferrals group where the calculation results are to be recorded.

5.  Click **Counters** to open the **Counter setup** form.

6.  In the **Expense code** field, select the relevant expense code.

7.  On the **Lines** FastTab, click **Add** and then select **Quantity** in the **Line type** field.

8.  In the **Operator** field, select \*.

9.  Click **Add** and then select **Price** in the **Line type** field.

10. In the **Output** field, select **Data output**.

## See also

[(RUS) Process incoming VAT by using the Proportional VAT deduction method](rus-process-incoming-vat-by-using-the-proportional-vat-deduction-method.md)

[(RUS) Create and post deferrals by using the Proportional VAT refund method](rus-create-and-post-deferrals-by-using-the-proportional-vat-refund-method.md)

  


