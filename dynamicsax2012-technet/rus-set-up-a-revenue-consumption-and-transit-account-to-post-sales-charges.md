---
title: (RUS) Set up a revenue, consumption, and transit account to post sales charges
TOCTitle: (RUS) Set up a revenue, consumption, and transit account to post sales charges
ms:assetid: e2617eb3-7d67-4e2f-bed8-3689e937a324
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923601(v=AX.60)
ms:contentKeyID: 53382725
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a revenue, consumption, and transit account to post sales charges 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Misc. charges posting in Accounts receivable** form to set up a revenue account, consumption account, and transit account, so that you can post sales charges. You can also specify a charges relation and account relation for the charges posting type.

1.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Charges posting**.

2.  In the **Misc. charges posting type** field, select the charges posting type.

3.  Press CTRL+N to create a ledger account for the selected charges posting type.

4.  In the **Account code** field, select an account relation from the following options:
    
      - **Table** – The account relation is for a specific customer.
    
      - **Group** – The account relation is for a list of customer groups.
    
      - **All** – The account relation is for all customers.

5.  In the **Account relation** field, select the customer or customer group to set up an account relation for.

6.  In the **Misc. charges relation** field, select a charges code relation from the following options:
    
      - **Table** – The posting is set up for a specific charges code.
    
      - **All** – The posting is set up for all charges codes.

7.  In the **Charges code** field, select the charges code.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>You can create a charges code in the <STRONG>Charges code</STRONG> form.</P>
    > <LI>
    > <P>This field is available only if you selected <STRONG>Table</STRONG> in the <STRONG>Misc. charges relation</STRONG> field.</P></LI></UL>



8.  In the **Main account** field, select the ledger account that the charges transactions are posted to.

9.  In the **Posting type** field, select the posting type to post charges.
    

    > [!NOTE]
    > <P>You can select posting type only if the <STRONG>Transit account</STRONG> option is selected in the <STRONG>Misc. charges posting type</STRONG> field.</P>



## See also

[(RUS) Set up a charges code by using a transit account](rus-set-up-a-charges-code-by-using-a-transit-account.md)

[(RUS) Set up a posting account for shipped items or items shipped offset](rus-set-up-a-posting-account-for-shipped-items-or-items-shipped-offset.md)

[(RUS) Misc. charges posting in Accounts receivable (form)](https://technet.microsoft.com/en-us/library/jj853185\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

