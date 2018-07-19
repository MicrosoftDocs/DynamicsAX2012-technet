---
title: (RUS) Set up parameters for advance holders
TOCTitle: (RUS) Set up parameters for advance holders
ms:assetid: 7b8e22c4-d224-4625-b305-0d384076149f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678387(v=AX.60)
ms:contentKeyID: 49387618
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters for advance holders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.
    

    > [!NOTE]
    > <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



2.  Click **Advance holders**, and then in the **Advance holders** area, in the **Posting profile** field, select the default profile to complete transactions for advance holders.
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-set-up-posting-profiles-for-accounting-vouchers.md">(RUS) Set up posting profiles for accounting vouchers</A>.</P>



3.  Select the **Set default advance holder** check box to set the current user as the advance holder.

4.  Select the **Advance holder sorting** check box to display the advance holders at the beginning of the list in the **Advance holders** form.

5.  Select the **Issue when balance is open** check box to allow issue of a cash advance to an advance holder who has an open positive balance.

6.  Select the **Settlement by profile** check box to settle transactions only with an identical posting profile.

7.  In the **Name** field under the **Balance closing via cash** field group, select the cash slip journal code. This journal code is used to generate cash disbursement slips and reimbursement slips when closing an advance holder's balances through cash.
    

    > [!NOTE]
    > <P>All journals are of the type <STRONG>Cash</STRONG>.</P>



8.  In the **Cash** field, select the cash account to determine the vouchers that are used for closing the balances for the advance holder.

9.  In the **Name** field under the **Balance closing via bank** field group, select the journal code for transactions to close the balances through a bank.

10. In the **Account** type field, select **Bank** to close the balances for an advance holder through a bank.

11. In the **Account** field, select the bank account code to close the balances for an advance holder through a bank.

12. Press CTRL+S or close the form.

## See also

[(RUS) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj923609\(v=ax.60\))

  


