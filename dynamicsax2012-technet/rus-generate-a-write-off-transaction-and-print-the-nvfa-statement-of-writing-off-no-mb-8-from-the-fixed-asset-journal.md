---
title: (RUS) Generate a write-off transaction and print the NVFA statement of writing off (No. MB-8) from the fixed asset journal
TOCTitle: (RUS) Generate a write-off transaction and print the NVFA statement of writing off (No. MB-8) from the fixed asset journal
ms:assetid: ae3d8f22-9789-4a19-a58e-cdf3387f42cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923578(v=AX.60)
ms:contentKeyID: 52075424
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- special rigging
- working clothes
- Write-off
---

# (RUS) Generate a write-off transaction and print the NVFA statement of writing off (No. MB-8) from the fixed asset journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to print the not valuable fixed asset (NVFA) Statement of writing off (No. MB-8) from the fixed asset (FA) journal after you enter disposal or write-off transactions. The report can also be printed from the **Working clothes**, **Special rigging**, or **Not valuable FAs** form for transactions that have a status of **Written off** or **Written off (dismantlement)**.

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  Create a new journal.

3.  In the **Name** field, select a journal name.

4.  Click **Lines**.

5.  Click **New** to open the **Add to journal** form.

6.  In the **Transaction date** field, select the transaction date.

7.  In the **Transaction type** field, select **Writing-off** or **Disposal (sale)**.

8.  In the **FA inventory number** field, select the inventory number of the fixed asset.

9.  Click **OK**. The value model lines for the asset record are created in the journal.

10. Click **Group operations** \> **Writing-off** to create write-off transactions.
    
    –or–
    
    Click **Group operations** \> **Disposal (sale)** to create disposal transactions.

11. In the **Disposal date** field, select the date of the disposal transaction.

12. Click **Select**, and then specify the selection criteria that are used to create transactions.

13. Click **OK**, and then click **OK** again to create disposal or write-off transactions.

14. In the **Journal voucher** form, click **Validate** \> **Validate** to validate the journal.

15. Click **Post** \> **Post** to post the journal.

16. Click **Print** \> **NVFA Statement of writing-off (No. MB-8)** to open the **NVFA Statement of writing-off (No. MB-8)** form.

17. In the **Order number** field, enter the order number that the disposal transaction is posted under.

18. In the **Resolution date** field, select the order date.

19. On the **Rows** tab, you can verify the document number, the fixed asset number, and the value model code.

20. On the **Officials** tab, you can view details about the officials who are assigned in the **Officials** form. You can also modify the employee details, if modification is required.

21. Click **OK** to generate the NVFA Statement of writing off (No. MB-8).

## See also

[(RUS) Special rigging (form)](https://technet.microsoft.com/en-us/library/jj923264\(v=ax.60\))

[(RUS) Working clothes (form)](https://technet.microsoft.com/en-us/library/jj923545\(v=ax.60\))

[(RUS) Not valuable FAs (form)](https://technet.microsoft.com/en-us/library/jj911484\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

