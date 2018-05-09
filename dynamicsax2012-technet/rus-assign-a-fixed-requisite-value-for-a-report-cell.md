---
title: (RUS) Assign a fixed requisite value for a report cell
TOCTitle: (RUS) Assign a fixed requisite value for a report cell
ms:assetid: 4353384c-e6e0-4ebd-95cc-f6ea8b776ef3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923411(v=AX.60)
ms:contentKeyID: 52075370
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed requisite
- requisite
---

# (RUS) Assign a fixed requisite value for a report cell 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Field setup** form to create a report cell that has a line type of **Fixed requisite** in the report that is generated using the financial reports generator (FRG).

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**. Select a report line, and then click **Setup**.
    
    –or–
    
    Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**. Click **Report**. Select a report line, and then click **Setup**.
    

    > [!NOTE]
    > <P>The <STRONG>Report</STRONG> button is available only if you select a report code in the <STRONG>Report code</STRONG> field and specify a file name and path for the report template in the <STRONG>File name</STRONG> field.</P>



2.  Click **New** to create a report cell, and then in the **Cell** field, enter a cell number.

3.  In the **Line type** field, select **Fixed requisite**.

4.  In the lower pane, click **Add**, and then in the **Operator** field, select a mathematical sign that is assigned to the cell value.

5.  In the **Line type** field, select **Fixed requisite**.

6.  In the **Fixed requisite** field, select the requisite for the report cell.

7.  In the **Period** field, select the period that the requisite is calculated for.
    

    > [!NOTE]
    > <P>The period that is specified in the <STRONG>Period</STRONG> field in the <STRONG>Functions</STRONG> form is used for the calculation. If you specified a period in the <STRONG>Functions</STRONG> form, you can leave the <STRONG>Period</STRONG> field blank in the <STRONG>Field setup</STRONG> form.</P>



## See also

[(EEUR) Create and copy report cells](eeur-create-and-copy-report-cells.md)

[(EEUR) Create report cell operations](eeur-create-report-cell-operations.md)

[(EEUR) Field setup (form)](https://technet.microsoft.com/en-us/library/jj910976\(v=ax.60\))

[(EEUR) Report (form)](https://technet.microsoft.com/en-us/library/jj911237\(v=ax.60\))

[(RUS) Functions (form)](https://technet.microsoft.com/en-us/library/jj710703\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

