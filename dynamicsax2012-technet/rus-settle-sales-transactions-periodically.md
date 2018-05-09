---
title: (RUS) Settle sales transactions periodically
TOCTitle: (RUS) Settle sales transactions periodically
ms:assetid: a9c805d8-d2c0-4026-a1a5-a03da464d755
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711487(v=AX.60)
ms:contentKeyID: 49387812
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Settle sales transactions periodically 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can perform periodic settlement of counteragent transactions by using the **Periodic settlement** form if the **Settlement** check box is selected in the **Customer posting profiles** form.

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Create a customer profile, or select an existing customer profile.
    

    > [!NOTE]
    > <P>For more information, see "Customer posting profile (form)" in the Applications and Business Processes Help.</P>



3.  On the **Table restrictions** tab, select the **Settlement** check box to enable automatic settlement of sales transactions.
    

    > [!NOTE]
    > <P>All vouchers with the selected profile will undergo periodic settlement if the <STRONG>Settlement</STRONG> parameter is activated.</P>



4.  Press CTRL+S or close the form.

5.  Click **Accounts receivable** \> **Periodic** \> **Settlement** \> **Periodic settlement**.

6.  In the **Settle by** field, select **Contract**.
    

    > [!NOTE]
    > <P>Periodic settlement is based on the first in, first out (FIFO) principle, in which the first invoice is settled with the first payment, if the registration numbers of the contracts in the settlement vouchers are concurrent. Also, any transactions that do not have a registration number and that do not belong to a contracts group are settled automatically by FIFO.</P>



7.  In the **From date** field, select the starting date for the settlement period.

8.  In the **To date** field, select the ending date for the settlement period.

9.  In the **Customer account** field, select the customer account.

10. In the **Contracts group** field, select the contract group.

11. In the **DVR** field, select the contract registration number. The contract number is displayed in the **Contract No.** field.

12. Click **Date principle** to open the **Specification on settlement** form.

13. In the **Settlement posting date** field, select the posting date from the following options:
    
      - **Latest date** – Settlement of the exchange adjustment transaction is performed on the last date of the transaction settlement. This option is selected by default.
    
      - **Today's date** – Settlement is performed on the current date
    
      - **Selected date** – Settlement is performed on the date that is specified in the **Selected date** field.

14. In the **Selected date** field, select the posting date.
    

    > [!NOTE]
    > <P>If you select <STRONG>Selected date</STRONG> in the <STRONG>Settlement posting date</STRONG> field, the date that you select in the <STRONG>Selected date</STRONG> field will be displayed in the <STRONG>Selected date of settlement</STRONG> field in the <STRONG>Periodic settlement</STRONG> form.</P>



15. Click **OK**.

16. Click **Select** to specify the criteria for customer transactions.

17. Click **OK** to perform the settlement.

18. Click **Accounts receivable** \> **Periodic** \> **Settlement** \> **Periodic reverse**.

19. In the **From date** field, select the starting date for the settlement period.

20. In the **To date** field, select the ending date for the settlement period.

21. In the **Customer account** field, select the customer account.

22. In the **Contracts group** field, select the contract group.

23. In the **DVR** field, select the contract registration number. The contract number is displayed in the **Contract No.** field.

24. Click **OK** to reverse the settlement.
    

    > [!NOTE]
    > <P>Periodic settlement and reverse vouchers are completed only for transactions with a corresponding currency code.</P>



## See also

[(RUS) Settle a sales transaction manually](rus-settle-a-sales-transaction-manually.md)

[(RUS) Adjust counteragent transactions in accounts receivable](rus-adjust-counteragent-transactions-in-accounts-receivable.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

