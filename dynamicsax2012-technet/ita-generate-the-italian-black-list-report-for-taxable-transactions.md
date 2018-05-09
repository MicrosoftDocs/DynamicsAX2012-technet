---
title: (ITA) Generate the "Italian black list" report for taxable transactions
TOCTitle: (ITA) Generate the "Italian black list" report for taxable transactions
ms:assetid: f44f0b48-3d9b-4278-bb40-8517aa1f0860
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227535(v=AX.60)
ms:contentKeyID: 36059989
ms.date: 05/21/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- (ITA)
- black list
- black list report
- Italian black list report
---

# (ITA) Generate the \"Italian black list\" report for taxable transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Italian black list report** to submit a list of your taxable transactions with legal entities in countries that have privileged taxation. These countries, also referred to as “black listed” countries by the Italian government, present a high risk from a tax standpoint.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in Microsoft Dynamics AX 2012 R3, AX 2012 R2 with hotfix <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2896989">KB2896989</A>, and AX 2012 with hotfix <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%3ben-us%3b2896989">KB2896989</A>. The first section below applies to AX 2012 R2 and AX 2012 without these hotfixes. The second section includes information about the updated functionality.</P>



## Generate the “Italian black list” report for taxable transactions in AX 2012 and AX 2012 R2

## Set up a number sequence for the “Italian black list” report

Use the **General ledger parameters** form to specify a number sequence reference that is used for the “Italian black list” report.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Number sequences** link.

3.  In the **Number sequence code** field, select a number sequence for the **Black list report ID** reference.

## Generate the “Italian black list” report

Use the following procedure to generate a monthly or quarterly report as an ASCII file. You can also view and update the transactions before you generate the report.

1.  Click **General ledger** \> **Reports** \> **External** \> **Italian black list report**.

2.  Create a new report.

3.  In the **From date** and **To date** fields, select the starting and ending dates of the reporting period.

4.  On the **General** FastTab, in the **Report** field group, specify the information in the following fields:
    
    1.  In the **Reporting period** field, select **Month** or **Quarter** as the reporting period.
    
    2.  In the **Declaration type** field, select the type of declaration from the following options:
        
          - **Integrative** – The report to be generated is a correction of a previously corrected report that was filed.
        
          - **Corrective** – The report to be generated is a correction of a previously generated original report.
        
          - **Original** – The report to be generated is a new report.
    
    3.  Select the **Change of frequency** check box to indicate that the reporting frequency is changed from monthly to quarterly or from quarterly to monthly.

5.  In cumulative update 4 or later for Microsoft Dynamics AX 2012: In the **Declarer** field group, specify the information in the following fields:
    
    1.  In the **Type of declarer** field, select one of the following options to indicate the way in which the “Italian black list” report is filed:
        
          - **Filing for same legal entity** – You file the report for the same legal entity for which the transactions are transferred.
        
          - **Filing for other legal entity** – You file the report on behalf of another legal entity.
        
          - **Filing through fiscal assistance center (CAF)** – The report is filed through a fiscal assistance center (CAF).
    
    2.  In the **Fiscal code** field, enter the fiscal code of the declarer.
    
    3.  In the **CAF inscription number** field, enter the five digit CAF inscription number.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Filing through fiscal assistance center (CAF)</STRONG> in the <STRONG>Type of declarer</STRONG> field.</P>

    
    4.  In the **CAF obligation** field, select one of the following options to indicate who prepares the “Italian black list” report:
        
          - **Declaration prepared by legal entity** – The declaration is prepared by the legal entity and filed through a CAF.
        
          - **Declaration prepared by declarer** – The declaration is prepared by a CAF on behalf of the legal entity.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Filing through fiscal assistance center (CAF)</STRONG> or <STRONG>Filing for other legal entity</STRONG> in the <STRONG>Type of declarer</STRONG> field.</P>

    
    5.  In the **CAF transmission date** field, select the transmission date for the selected declarer type.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Filing through fiscal assistance center (CAF)</STRONG> or <STRONG>Filing for other legal entity</STRONG> in the <STRONG>Type of declarer</STRONG> field.</P>



6.  In the **Writer** field group, specify the information in the following fields:
    
    1.  In the **Writer** field, select the name of the employee who is responsible for filing the report.
    
    2.  In the **Writer fiscal code** and **Writer role** fields, specify the fiscal code of the employee and select the role of the employee. For example, **Legal representative**, **Fiscal representative**, or **Public representative**.
    
    3.  In the **Place of birth** and **Province of birth** fields, specify the place of birth and province of birth of the employee.
    
    4.  In the **Town or country/region of residence**, **Residence county**, **Postal code**, and **Address** fields, enter the town or country/region of residence, select the residence county, and then enter the postal code and residential address of the employee.

7.  Click **Transfer** to transfer the customer and vendor invoice transactions to the **Transactions** FastTab based on the criteria that are specified on the **General** FastTab. Only transactions that are associated with a sales tax code are displayed on the report. Verify the transactions and make changes, if required.
    

    > [!NOTE]
    > <P>To include additional transactions, click <STRONG>Add</STRONG> on the <STRONG>Transactions</STRONG> FastTab.</P>



8.  Optional: Click **Apply threshold** to exclude invoices from the “Italian black list” report that are below the threshold amount that is specified in the **Threshold amount** field on the **General** FastTab.

9.  Click **Report**. On the **Italian black list report**, select the **Final export** check box to generate and export the report as an ASCII file.
    

    > [!NOTE]
    > <P>To verify the report before you generate and export it, clear the <STRONG>Final export</STRONG> check box, and then click <STRONG>OK</STRONG>.</P>



10. In the **File name** field, specify the path and file name for the report, and then click **OK** to generate the report.

## Generate the “Italian black list” report for taxable transactions in AX 2012 R3, AX 2012 R2 with hotfix KB2896989, and AX 2012 with hotfix KB2896989

## Set up a number sequence for the “Italian black list” report

Use the **General ledger parameters** form to specify a number sequence reference that is used for the “Italian black list” report.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Number sequences** link.

3.  In the **Number sequence code** field, select a number sequence for the **Black list report ID** reference.

## Generate the “Italian black list” report

Use the following procedure to generate a monthly or quarterly “Italian black list” report as an ASCII file. You can view and update the transactions before you generate the report.

1.  Click **General ledger** \> **Reports** \> **External** \> **Italian black list report**.

2.  Create a new report.

3.  In the **From date** field, select the starting date of the reporting period.

4.  On the **General** FastTab, in the **Legal entity designation** field, enter the designation of the legal entity.

5.  In the **Declarer** field group, specify the information in the following fields:
    
    1.  In the **Type of declarer** field, select one of the following options to indicate the type of declarer that files the “Italian black list” report:
        
          - **Filing for same legal entity** – You file the report for the same legal entity for which the transactions are transferred.
        
          - **Filing through fiscal assistance center (CAF)** – The report is filed through a CAF.
    
    2.  In the **CAF fiscal code** field, enter the fiscal code of the CAF.
    
    3.  In the **CAF obligation** field, select one of the following options to indicate who prepares the “Italian black list” report:
        
          - **Declaration prepared by legal entity** – The declaration is prepared by the legal entity and filed through a CAF.
        
          - **Declaration prepared by declarer** – The declaration is prepared by a CAF on behalf of the legal entity.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Filing through fiscal assistance center (CAF)</STRONG> in the <STRONG>Type of declarer</STRONG> field.</P>

    
    4.  In the **CAF inscription number** field, enter the five digit CAF inscription number.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Filing through fiscal assistance center (CAF)</STRONG> in the <STRONG>Type of declarer</STRONG> field.</P>

    
    5.  In the **CAF transmission date** field, select the transmission date for the selected declarer type.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Filing through fiscal assistance center (CAF)</STRONG> in the <STRONG>Type of declarer</STRONG> field.</P>



6.  In the **Report** field group, specify the information in the following fields:
    
    1.  In the **Reporting period** field, select **Month** or **Quarter** as the reporting period.
    
    2.  In the **Report type** field, select the type of report from the following options:
        
          - **Original** – The report to be generated is a new report.
        
          - **Replacement** – The report to be generated is a correction of a previously generated original report.
        
          - **Cancellation** – The report to be generated is a cancellation of a previously generated report that was filed.
    
    3.  In the **Original report number** field, enter the number of the original report that was generated.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Replacement</STRONG> or <STRONG>Cancellation</STRONG> in the <STRONG>Report type</STRONG> field.</P>

    
    4.  In the **Original report document number** field, enter the number of the original report document that is being replaced or canceled.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Replacement</STRONG> or <STRONG>Cancellation</STRONG> in the <STRONG>Report type</STRONG> field.</P>

    
    5.  In the **ATECOFIN Code** field, enter the classification of economic activity (ATECOFIN) code for reporting.
    
    6.  Optional: In the **Threshold amount** field, enter the threshold amount for the invoices that can be included on the report.

7.  In the **Writer** field group, specify the information in the following fields:
    
    1.  In the **Writer** field, select the name of the employee who is responsible for filing the report.
    
    2.  Select the **Legal entity** check box to indicate that the writer of the report is the legal entity. If you select this check box, the **Place of birth** and **Province of birth** fields are not available and the **Writer designation** field is available.
    
    3.  In the **Writer fiscal code**, **Writer designation**, and **Writer role** fields, specify the fiscal code of the employee, enter the designation of the employee, and select the role of the employee. For example, **Legal representative**, **Fiscal representative**, or **Public representative**.
    
    4.  In the **Place of birth** and **Province of birth** fields, specify the place of birth and province of birth of the employee.
        

        > [!NOTE]
        > <P>These fields are available only if you select the <STRONG>Legal entity</STRONG> check box.</P>

    
    5.  In the **Town or country/region of residence** field, enter the town or country/region where the employee resides.

8.  In the **Dates** field group, in the **Procedure start date** and **Procedure end date** fields, specify the starting and ending dates of the procedure to submit the report if the report is submitted by a person or company on behalf of the legal entity.

9.  Click **Transfer** to transfer the customer and vendor invoice transactions to the **Transactions** FastTab based on the criteria that are specified on the **General** FastTab. Only transactions that are associated with a sales tax code are displayed on the report. Verify the transactions and make changes, if required.
    

    > [!NOTE]
    > <P>To include additional transactions, click <STRONG>Add</STRONG> on the <STRONG>Transactions</STRONG> FastTab.</P>



10. Optional: Click **Apply threshold** to exclude invoices from the “Italian black list” report that are below the threshold amount that is specified in the **Threshold amount** field on the **General** FastTab.

11. Click **Report**. On the **Italian black list report**, select the **Final export** check box to generate and export the report as an ASCII file.
    

    > [!NOTE]
    > <P>To verify the report before you generate and export it, clear the <STRONG>Final export</STRONG> check box, and then click <STRONG>OK</STRONG>.</P>



12. In the **File name** field, specify the path and file name for the report, and then click **OK** to generate the report.

## See also

[(ITA) Italian black list report (form)](https://technet.microsoft.com/en-us/library/hh208823\(v=ax.60\))

[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

