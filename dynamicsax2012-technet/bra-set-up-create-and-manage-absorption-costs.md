---
title: (BRA) Set up, create, and manage absorption costs
TOCTitle: (BRA) Set up, create, and manage absorption costs
ms:assetid: 26ed04bf-e5bf-4b59-8f10-1a0f9bf776cb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710437(v=AX.60)
ms:contentKeyID: 49384329
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00001
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up, create, and manage absorption costs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate and post the direct and indirect costs that are incurred in the production orders for a fiscal period. The final manufacturing costs are registered in the ledger at the end of the fiscal period. You can calculate the absorption costs by allocating the total manufacturing costs to the products that are manufactured during a fiscal period.

## Set up a number sequence for absorption costs

Use this procedure to set up the number sequence code for cost absorption journals.

1.  Click **Production control** \> **Setup** \> **Absorption costs** \> **Parameters**.

2.  In the **Number sequence code** field, select the number sequence code to use for the cost absorption journal.

## Set up a cost center for absorption costs

Use this procedure to set up a cost type for a cost center. You can use the **Cost center** form to set up cost centers for absorption costs. For more information, see [Operating units (form)](https://technet.microsoft.com/en-us/library/hh208817\(v=ax.60\)).

1.  Click **Production control** \> **Setup** \> **Absorption costs** \> **Cost centers**.

2.  Select the cost center to use to post absorption costs.

3.  In the **Cost type** field, select the type of cost for the cost center.

## Set up journal names for absorption costs

Use this procedure to set up journal names for absorption costs.

1.  Click **Production control** \> **Setup** \> **Absorption costs** \> **Journal names**.

2.  Press CTRL+N to create a record.

3.  In the **Name** field, enter a name for the journal.
    

    > [!NOTE]
    > <P>The <STRONG>Journal type</STRONG> field is updated with the default journal type that is used for absorption costs. The default journal type is <STRONG>Indirect costs</STRONG>.</P>



4.  In the **Description** field, enter a brief description for the journal.

5.  In the **Voucher series** field, select the number sequence code to use for the journal.

6.  In the **Selection by** field, indicate whether a new voucher is selected during entry or after posting.

7.  In the **Detail level** field, select the method to use to summarize the details of the journal.

## Create the cost absorption journal

Use this procedure to create and post a cost absorption journal.

1.  Click **Production control** \> **Periodic** \> **Absorption costs** \> **Cost absorption journal**.

2.  Press CTRL+N to create a journal.

3.  On the **Overview** tab, in the **Name** field, select the name of the cost absorption journal.

4.  In the **Month/Year to close** field, select the month and year that the costs are posted for.

5.  Click **Lines** to open the **Journal lines** form, and then specify values in the following fields:
    
      - **Date** – The date on which to post the journal line.
    
      - **Ledger account** – The ledger account number to post the journal line to.
    
      - **Cost center** – The cost center number to use to post the journal line.
    
      - **Cost amount** – The cost amount for the journal line.

6.  Click **Post** \> **OK** to post the journal line.
    

    > [!NOTE]
    > <P>You can view the type of absorbed cost that is posted to a work center, the corresponding cost center that the work center is associated with, the hourly rate, and the planned capacity for the work center details in the <STRONG>Absorbed costs</STRONG> form.</P>



## Close absorption costs

You can post the absorption costs for a specific month and year to the ledger. You can specify the transfer account and transfer offset account in the **Accounts - WIP** and **Accounts - costing** fields in the **Resources** form. For more information, see [Resources (form)](https://technet.microsoft.com/en-us/library/aa557962\(v=ax.60\)).

1.  Click **Production control** \> **Periodic** \> **Absorption costs** \> **Absorption costs - monthly closing**.

2.  In the **Month/Year to close** field, select the month and year to post the absorbed costs for.

3.  Click **OK** to post the absorption costs for the selected month and year.

## Cancel absorbed costs

Use this procedure to cancel the absorbed costs that are not posted to the ledger for a specific month and year. You cannot cancel the absorbed costs after the monthly closing is completed.

1.  Click **Production control** \> **Periodic** \> **Absorption costs** \> **Absorbed costs cancellation**.

2.  In the **Month/Year to cancel** field, select the month and year to cancel the absorbed costs for.

3.  Click **OK** to cancel the absorbed costs for the selected month and year.

## See also

[(BRA) Cost absorption journal (form)](https://technet.microsoft.com/en-us/library/jj710612\(v=ax.60\))

[(BRA) Cost absorption journal lines (form)](https://technet.microsoft.com/en-us/library/jj663929\(v=ax.60\))

[(BRA) Cost absorption parameters (form)](https://technet.microsoft.com/en-us/library/jj710572\(v=ax.60\))

[(BRA) Absorption costs - Monthly closing (form)](https://technet.microsoft.com/en-us/library/jj663935\(v=ax.60\))

[(BRA) Absorbed costs cancellation (form)](https://technet.microsoft.com/en-us/library/jj710580\(v=ax.60\))

[(BRA) Absorbed costs (form)](https://technet.microsoft.com/en-us/library/jj663941\(v=ax.60\))

[(BRA) Journal names (form)](https://technet.microsoft.com/en-us/library/jj710533\(v=ax.60\))

  


