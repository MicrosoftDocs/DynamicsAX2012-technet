---
title: (RUS) Settle a sales transaction manually
TOCTitle: (RUS) Settle a sales transaction manually
ms:assetid: 3a4b3690-20ac-49e6-81ae-99b5674e446a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665295(v=AX.60)
ms:contentKeyID: 49387384
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Settle a sales transaction manually 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can settle counteragent transactions manually by using the **Facture and payment settlement** form if the **Automatic settlement** check box is cleared in the **Accounts receivable parameters** form.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  On the **Settlement** tab, clear the **Automatic settlement** check box.

3.  Press CTRL+S or close the form.

4.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    

    > [!NOTE]
    > <P>For more information, see "Customers (form)" in the Applications and Business Processes Help.</P>



5.  Select a customer account, and then click **Functions** \> **Facture and payment settlement** to open the **Facture and payment settlement** form.

6.  In the **Look in** field, select **Agreement**.

7.  In the **Contracts group** field, select the contract group.

8.  In the **DVR** field, select the contract registration number.

9.  Select the **Mark** check box to select the transaction for settlement.
    

    > [!NOTE]
    > <P>Select the reimbursement transaction for settlement in the upper pane and the disbursement transaction in the lower pane.</P>



10. Click **Update** to perform settle the counteragent transaction.
    

    > [!NOTE]
    > <P>If an exchange adjustment is performed from the settlement transaction, a reference to the contract group and registration number of the contract will be stored in the exchange adjustment transaction.</P>



## See also

[(RUS) Settle sales transactions periodically](rus-settle-sales-transactions-periodically.md)

[(RUS) Adjust counteragent transactions in accounts receivable](rus-adjust-counteragent-transactions-in-accounts-receivable.md)

  


