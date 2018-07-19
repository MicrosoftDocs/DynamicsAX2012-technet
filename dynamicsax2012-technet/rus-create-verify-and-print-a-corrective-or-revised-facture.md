---
title: (RUS) Create, verify, and print a corrective or revised facture
TOCTitle: (RUS) Create, verify, and print a corrective or revised facture
ms:assetid: c40dddc1-3316-496b-acfc-b7483b45f76a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923587(v=AX.60)
ms:contentKeyID: 52075430
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create, verify, and print a corrective or revised facture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and print corrective and revising factures based on credit notes, corrective invoices, and tax correction transactions. You can also revise either the lines or the header of an existing facture. All of the corrections and revisions of a facture are made in a specific order. You can view the details of the changes and the interim state of the facture.

Use the following procedures to create, verify, and print a corrective or revised facture.

## Create a corrective or revised facture for a purchase order

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double-click a purchase order. To create a new purchase order, on the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**. For more information, see [Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\)).

2.  On the **Invoice** tab, click **Facture** to open the **Update facture** form.

3.  Click **Header view**.

4.  On the **Additional** FastTab, in the **Correction type** field, select the type of facture correction.

5.  In the **Invoice** field, select the number of the invoice that must be corrected or revised.

6.  In the **Facture** field, select the facture that requires correction.

7.  Click **Facture** \> **Post** to update and post the corrective facture.

## Create a corrective or revised facture for a vendor invoice

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Double-click a purchase order.

2.  Click **Invoice**, and then click **Facture** to open the **Update facture** form.

3.  Select the **Corrective document** check box to indicate that the facture is a corrective or revised facture.

4.  In the **Correction type** field, select the type of facture correction.

5.  In the **Facture** field, select the facture that requires correction.

6.  In the **Facture date** field, select the facture date.

7.  Click **Posting** \> **Update** to update and post the corrective facture.

## Create a corrective or revised facture for a sales order

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. To open an existing sales order, double-click the sales order. To create a new sales order, on the **Action Pane**, on the **Sales order** tab, click **Sales order**. For more information, see [Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\)).

2.  Click **Invoice**, and then click **Facture** to open the **Update facture** form.

3.  In the lower pane, on the **Additional** tab, in the **Correction type** field, select the type of facture correction.

4.  In the **Invoice** field, select the invoice that requires correction.

5.  In the **Invoice date** field, select the invoice date.

6.  In the **Facture** field, select the facture that requires correction.
    

    > [!NOTE]
    > <P>The facture number is updated automatically if the facture consists of only one invoice.</P>



7.  In the **Facture date** field, select the facture date.

8.  Click **OK** to create the corrective or revised facture for a customer invoice.

## Create a corrective or revised facture for a customer invoice

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. To open an existing sales order, double-click the sales order.

2.  Click **Invoice**, and then click **Facture** to open the **Update facture** form.

3.  Select the **Corrective document** check box to indicate that the facture is a corrective or revised facture.

4.  In the **Correction type** field, select the type of facture correction.

5.  In the **Facture** field, select the facture that requires correction.

6.  In the **Facture date** field, select the facture date.

7.  Click **Posting** \> **Update** to update and post the corrective facture.

## Revise a facture in the Facture journal form

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Facture**.
    
    –or–
    
    Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Facture**.

2.  In the facture header, select a facture line, and then click **Revise header** to open the **Update facture** form.

3.  In the **Shipper** field, select the account number of the customer or vendor who is the shipper.

4.  In the **Consignee** field, select the account number of the customer or vendor who is the consignee.

5.  Click **Posting** \> **Update** to update and post the facture.

## Verify a corrective or revised facture in the Facture journal form

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Facture**.
    
    –or–
    
    Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Facture**.

2.  Select the **Show correction history** check box to view the history of all facture corrections. The original facture and the associated corrective factures are displayed.

3.  Select the **Show revised** check box to view the history of facture revisions. All revised facture lines are displayed in gray.

4.  Click the **Totals after correction** tab to view the total facture amount details after the correction. In the lower pane, click the **Line after correction** tab to view the amount for each facture line after the correction.

5.  Click **Final state** to open the **Facture final state** form, where you can view the final status of all facture lines, including all corrective and revised factures.

## Print a corrective or revised facture

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Facture**.
    
    –or–
    
    Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Facture**.

2.  In the facture header, select a facture, and then click **Print** \> **Correction** to print a corrective facture.

3.  Click **Print** \> **Original** to print the original facture.
    
    –or–
    
    Click **Print** \> **Copy** to print a copy of the facture.

## See also

[(RUS) Facture journal (form)](https://technet.microsoft.com/en-us/library/jj923567\(v=ax.60\))

[(RUS) Set up parameters to create corrective and revised factures](rus-set-up-parameters-to-create-corrective-and-revised-factures.md)

  


