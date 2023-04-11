---
title: (RUS) Perform an outgoing VAT processing transaction
TOCTitle: (RUS) Perform an outgoing VAT processing transaction
ms:assetid: f0127d0c-88fc-4d87-bfd7-698a2c49fbc0
ms:mtpsurl: https://technet.microsoft.com/library/JJ856121(v=AX.60)
ms:contentKeyID: 50406419
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- VAT
- outgoing VAT
- outgoing VAT transaction
audience: Application User
ms.search.region: Russia
---

# (RUS) Perform an outgoing VAT processing transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define the parameters for outgoing value-added tax (VAT) processing operations by using the **Parameters of VAT process** form, and then use the **Outgoing VAT processing** form to process the VAT transactions. You can also use the **Sales book** form for statutory VAT reporting. The transactions for export factures are registered in the sales book. Use the following procedures to set up parameters for outgoing VAT processing and to create an outgoing VAT processing transaction.

## Set up parameters for outgoing VAT processing to calculate a restored VAT amount

1.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Parameters of VAT process**.

2.  Press CTRL+N to create a new parameter for the VAT process.

3.  In the **VAT operation code** field, enter an operation code for outgoing VAT processing.

4.  In the **Operation type** field, select an operation for outgoing VAT processing, such as **VAT restoration**.

5.  In the **Description** field, enter a description of the transaction.

6.  In the **Restoration type** field, select the VAT restoration type.

7.  Select the **By default** check box to define the default operation code for the selected restoration type.

8.  Select the **Include in book** check box to include the specified operation in the sales book.

9.  Click the **Setup** tab.

10. In the **Account code** field, select the account code from the following options:
    
      - **Table** – The sales tax code attached to the transaction to restore VAT amounts.
    
      - **Group** – The sales tax group attached to a group of transactions to restore VAT amounts.
    
      - **All** – The sales tax code that is attached to all transactions that restore the VAT amounts.

11. In the **Account/Group number** field, select the sales tax code or group for the transaction to restore VAT amounts.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>



12. In the **Main account** field, select the ledger account number for posting outgoing VAT processing transactions, and in the **Offset account** field, select the offset account number for posting outgoing VAT processing transactions.

13. Select the **Default dimension** check box to use the dimensions values from the transaction and overwrite the dimensions value that is set in the **Financial dimensions** form.

## Create an outgoing VAT processing transaction

1.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Outgoing VAT processing**.

2.  Click **Select...** to open the **Outgoing VAT processing - select data for period** form.

3.  In the **From date** field, select the starting date for the tax processing period, and in the **To date** field, select the ending date for the tax processing period.

4.  Select the **Include unpaid export factures from previous periods** check box to include unpaid export factures from previous periods in the sales books.

5.  Click **Select** to specify the criteria for selecting the factures for processing.

6.  Click **OK** to view the factures to be processed in the **Sales book** (**Outgoing VAT processing**) form for the specified period.

7.  Select the **Marked** check box to mark the facture for outgoing VAT processing.

8.  Click **Post** to post the VAT processing transaction.

9.  In the **Transaction date** field, select the date to post the transaction, and then click **OK**.
    

    > [!NOTE]
    > <P>You can cancel the outgoing VAT processing operation for an export facture by using the <STRONG>Cancellation of preliminary processing</STRONG> form.</P>



10. Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **VAT processing log**. You can view the processing and canceling operations for outgoing VAT. For more information, see [(RUS) VAT processing log (form)](https://technet.microsoft.com/library/jj923606\(v=ax.60\)).

11. Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **Sales books journal**.

12. Create a new sales book. For more information, see [(RUS) Create a sales book](rus-create-a-sales-book.md).

13. Click **Totals** to view the domestic and export sales amounts, which are taxable at the standard and export rates.

## See also

[(RUS) Sales books journal (form)](https://technet.microsoft.com/library/jj853161\(v=ax.60\))

  


