---
title: (RUS) Set up a number sequence group for cash management
TOCTitle: (RUS) Set up a number sequence group for cash management
ms:assetid: e415ee4b-0740-4a1a-b5ef-209680c9fba0
ms:mtpsurl: https://technet.microsoft.com/library/JJ711706(v=AX.60)
ms:contentKeyID: 49388029
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a number sequence group for cash management 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can assign number sequence groups to ensure that documents and vouchers in different cash accounts have a unique numbering format.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**. Click **Number sequences**, and then click **Group** to open the **Number sequence groups** form
    

    > [!NOTE]
    > <P>The <STRONG>Group</STRONG> button is available only when the cash account-related references − <STRONG>Cash reimbursement slips</STRONG>, <STRONG>Cash disbursement slips</STRONG>, <STRONG>Cash correction voucher</STRONG>, and <STRONG>Cash exchange adjustment slip</STRONG> − are selected in the <STRONG>Reference</STRONG> field.</P>



2.  Click CTRL+N to create a new number sequence group.

3.  In the **Group** field, enter a unique group name for allocation of the new number sequence to a customer or vendor.

4.  In the **Description** field, enter the description of the number sequence group.

5.  Click the **Reference** tab, and then select the number sequence codes that will be used to formulate the numbers for the group that is selected in the **Reference** field.
    

    > [!NOTE]
    > <P>The reference selected in the <STRONG>Bank parameters</STRONG> form is displayed in the <STRONG>Reference</STRONG> field.</P>



6.  In the **Number sequence code** field, select the current number sequence code to be used with references.

7.  Press CTRL+S or close the form.

## See also

[(RUS) Set up a cash account](rus-set-up-a-cash-account.md)

[(RUS) Cash and bank management parameters (modified form)](https://technet.microsoft.com/library/jj711566\(v=ax.60\))

  


