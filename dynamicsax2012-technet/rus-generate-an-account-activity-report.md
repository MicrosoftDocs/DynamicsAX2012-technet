---
title: (RUS) Generate an account activity report
TOCTitle: (RUS) Generate an account activity report
ms:assetid: 26e2e68e-c65c-4b21-bc9a-cafadd0d52a7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665214(v=AX.60)
ms:contentKeyID: 49387304
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate an account activity report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The turnover sheet with correspondence is a basic component of the accounting reports. It contains activity information for all accounts during the accounting period.

1.  Click **General ledger** \> **Inquiries** \> **Account activity** \> **Turnover sheet with correspondence**.

2.  In the **Date interval code** field, select the date interval code from the date intervals directory.

3.  In the **From date** field, select the start of the report generation period.
    

    > [!NOTE]
    > <P>This field is selected manually or inserted from the selected date interval code.</P>



4.  In the **To date** field, select the end of the report generation period.
    

    > [!NOTE]
    > <P>This field is selected manually or inserted from the selected date interval code.</P>



5.  In the **Currency type** field, select the currency type for the report from the following options:
    
      - **Default currency**
    
      - **Secondary currency**
    
      - **Indicated currency**

6.  In the **Currency** field, select the transaction currency.
    

    > [!NOTE]
    > <P>This field is activated only if you select <STRONG>Indicated currency</STRONG> in the <STRONG>Currency type</STRONG> field.</P>



7.  Select the **To debit accounts** check box so that the debit for the selected accounts appears as a header line.
    

    > [!NOTE]
    > <P>If the check box is not selected, the debit for the selected accounts appears in the column.</P>



8.  In the **Posting layer** field, select the accounting type.

9.  In the **Department** field, select the dimension code if vouchers with specific codes must be selected for the report.

10. In the **Cost center** field, select the dimension code if vouchers with specific codes must be selected for the report.

11. In the **Purpose** field, select the dimension code if vouchers with specific codes must be selected for the report.
    

    > [!NOTE]
    > <P>If the <STRONG>Department</STRONG>, <STRONG>Cost Center</STRONG>, and <STRONG>Purpose</STRONG> fields are left blank, transactions with any dimensions codes are selected for the report.</P>



12. Select the **Print ranges** check box to view the query terms when printing the report.

13. Select the **Delete zero line** check box if you do not want to print lines or columns with zero values.

14. Select the **Total accounts** to total the accounts.

15. Click **OK** to generate the report.
    

    > [!NOTE]
    > <P>Double-click a cell in the report to view the ledger transactions that generated the activity.</P>



16. Click **Select** to change the parameters for report generation.

17. Click **Print** to print the report.

## See also

[(RUS) Turnover sheet with correspondence (form)](https://technet.microsoft.com/en-us/library/jj665416\(v=ax.60\))

  


