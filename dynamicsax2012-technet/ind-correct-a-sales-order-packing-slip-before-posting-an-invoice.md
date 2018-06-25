---
title: (IND) Correct a sales order packing slip before posting an invoice
TOCTitle: (IND) Correct a sales order packing slip before posting an invoice
ms:assetid: 43463b6e-d1c5-4b55-be78-909385d32838
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664657(v=AX.60)
ms:contentKeyID: 49385731
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Correct a sales order packing slip before posting an invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can correct a sales order packing slip without having to create a new packing slip ID. Excise tax is calculated, and the excise registers are updated, at the packing slip level, based on the type of calculation date that is selected in the **General ledger parameters** form.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **Action Pane**, on the **Pick and pack** tab, in the **Journals** group, click **Packing slip journal**.

3.  In the **Packing slip journal** form, select the packing slip record, and then click **Correct**.

4.  In the **Correct packing slip – Packing slip %1, %2** form, on the **Lines** tab, in the **Update** field, enter the new quantity. Then click **OK**.

5.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

6.  In the **Excise register inquiry** form, in the **Register** field, select **RG23A Part - I**.

7.  Specify the required data for the RG23A – Part I register, and then click **OK** to open the **RG23A Part - I transactions** form. The excise register is updated with three lines that refer to the same packing slip number. Each line has a different register ID and includes the tax amounts that relate to quantity.
    
    The excise register is updated with the following register IDs:
    
      - The original quantity and tax amount
    
      - The reversed quantity and tax amount
    
      - The corrected quantity and tax amount

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

