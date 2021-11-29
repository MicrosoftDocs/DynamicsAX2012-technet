---
title: (RUS) Calculate the exchange rate difference for a customer
TOCTitle: (RUS) Calculate the exchange rate difference for a customer
ms:assetid: 2ca61316-701e-47c7-a0ba-c1592b7a50d7
ms:mtpsurl: https://technet.microsoft.com/library/JJ665234(v=AX.60)
ms:contentKeyID: 49387323
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the exchange rate difference for a customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can use the **Exchange adjustment** form to calculate the exchange rate difference for a customer. The exchange adjustment is calculated at the end of a period according to the rate specified at the period end date.

1.  Click **Accounts receivable** \> **Periodic** \> **Foreign currency revaluation**.

2.  In the **Method** field, select the **Standard** method.

3.  In the **Considered date** field, select the date to adjust the open transaction. The same date is used to post the adjusted transaction.

4.  In the **Date of rate** field, select the date that determines the exchange rate to be used to revalue the voucher.

5.  In the **Transaction text** field, enter the text that describes the exchange adjustment transaction.
    

    > [!NOTE]
    > <P>If this field is left blank, then it is automatically filled with the standard text for exchange rate correction, and the number of the revaluated document.</P>



6.  In the **Notes** field, enter any additional information about the transaction.

7.  In the **Use posting profile from** field, select the posting profile for the transaction from the following options:
    
      - **Posting** − The profile of the posted open transaction is used for the exchange adjustment.
    
      - **Select** − The profile selected in the **Posting profile** field is used for the exchange adjustment.

8.  In the **Posting profile** field, select the posting profile to be used.
    

    > [!NOTE]
    > <P>If you select a posting profile in the <STRONG>Use posting profile from</STRONG> field, the exchange adjustment transaction is based on the posting profile in that field.</P>



9.  In the **Dimension** field, select the dimensions that are posted to the exchange adjustment transactions from the following options:
    
      - **None** – In the exchange adjustment voucher, the line dimension is not dependent on the dimension in the original voucher.
    
      - **Table** – In the exchange adjustment voucher, the line dimension is inherited from the dimension of the customer account.
    
      - **Posting** – In the exchange adjustment voucher, the line dimension is inherited from the dimension in the original voucher.

10. Select the **Print** check box to print the report.

11. Click **OK** to open the **Customer – Exchange adjustment** form.

12. Click **Select** to specify the criteria for exchange adjustment, if required.

13. Click **OK** to revalue the selected transaction.

14. In the **Exchange adjustment** form, click **Voucher** to open the **Voucher transactions** form to view the resulting ledger transactions for exchange adjustment.

15. Press CTRL+S or close the form.

16. In the **Exchange adjustment** form, click **Transactions** to open the **Customer transactions** form to view the resulting customer transactions for exchange adjustment.

17. Press CTRL+S or close the form.

18. In the **Exchange adjustment** form, click **Simulation** to open the **Customer - Exchange adjustment simulation** form.
    

    > [!NOTE]
    > <P>This button is available only if you select <STRONG>Standard</STRONG> in the <STRONG>General ledger parameters</STRONG> form, in the <STRONG>Calculation method</STRONG> field on the <STRONG>Ledger</STRONG> tab.</P>



19. In the **Method** field, select a method for exchange adjustment.

20. In the **Considered date** field, select the voucher posting date.

21. In the **Date of rate** field, select the exchange date.

22. Click **Select** to define the customer account, currency, and fixed rate.

23. Click **OK** to display the customer transaction details in the **Customer - Exchange adjustment simulation** form.

24. Click **Parameters** to specify the report output.

25. Click **OK** to generate the **Exchange adjustment simulation** report.

  


