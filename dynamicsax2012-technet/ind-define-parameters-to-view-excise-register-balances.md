---
title: (IND) Define parameters to view excise register balances
TOCTitle: (IND) Define parameters to view excise register balances
ms:assetid: c06f0ae9-3e70-4619-9a91-bd1853223a57
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664862(v=AX.60)
ms:contentKeyID: 49386192
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Define parameters to view excise register balances [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a query to view the balances of excise registers, you must first select the parameters for the query in the **Excise registers balance inquiry** form. These parameters include the tax ledger posting group, the Excise Control Code (ECC) number, and the date. The balance amounts that are displayed in the **Excise balance** form are based on the parameters that are set up in the **Excise registers balance inquiry** form.

1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register balance**.

2.  In the **Excise registers balance inquiry** form, select a query to modify, or enter a new query in the **Select query** field.

3.  In the **Tax ledger posting group** field, select the tax ledger posting group.

4.  In the **ECC number** field, select the excise control code.

5.  In the **Date** field, select the date.
    
    The balance amounts are filtered based on the tax ledger posting group, ECC number, and date. These balance amounts are displayed in the **Excise balance** form when you click **OK**.

6.  Select the **Header note** check box to enter the text for a header note. Then enter the text for the header note in the **Header note** field. The header note is displayed in the **Excise balance** form.

7.  Select the **Footer note** check box to enter the text for a footer note. Then enter the text for the footer note in the **Footer note** field. The footer note is displayed in the **Excise balance** form.

8.  Click **Modify...** to modify, save, or delete the query.

9.  Click **Reset** to clear the values that you have entered in the form.

10. Click **OK** to open the **Excise balance** form.

## See also

[(IND) Excise registers balance inquiry (form)](https://technet.microsoft.com/en-us/library/jj664516\(v=ax.60\))

[(IND) Excise balance (form)](https://technet.microsoft.com/en-us/library/jj664540\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

