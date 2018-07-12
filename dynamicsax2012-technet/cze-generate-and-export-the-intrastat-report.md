---
title: (CZE) Generate and export the Intrastat report
TOCTitle: (CZE) Generate and export the Intrastat report
ms:assetid: 0cd2a6f8-431f-42d4-921b-50d2b626e6a1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664170(v=AX.60)
ms:contentKeyID: 49384754
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic
---

# (CZE) Generate and export the Intrastat report 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use the following procedure to generate the Intrastat report for a Czech legal entity and export it as an XML file or as a CSV file. The Intrastat report contains a summary of Intrastat transactions for the internal transfer of items between European Union (EU) member states.


> [!NOTE]
> <P>In AX 2012 R3: The Intrastat report is exported in the XML file format or the CSV file format depending on the format that you select in the <STRONG>XSLT ID</STRONG> field in the <STRONG>Intrastat</STRONG> area in the <STRONG>Foreign trade parameters</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/jj910988(v=ax.60)">(CZE) Foreign trade parameters (modified form)</A>.</P>



1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer CZ** to transfer Intrastat transactions to the **Intrastat** form.

3.  Select one or all of the following transaction type check boxes to transfer the transactions for those types to the **Intrastat** form:
    
      - **Free text invoice**
    
      - **Customer invoice**
    
      - **Customer packing slips**
    
      - **Vendor invoice**
    
      - **Vendor product receipts**
    
      - **Project invoice**
    
      - **Transfer order**

4.  Optional: Click **Select** to specify additional criteria, such as transaction date, shipment date, and posting date to select the transactions that are transferred to the **Intrastat** form.

5.  Click **OK** to transfer the transactions for the selected transaction types.

6.  In the **Intrastat** form, click **Output** \> **Report** to open the **Intrastat report** form.

7.  In the **From date** field, select the starting date of the month to generate the Intrastat report for. The last date of the month is updated in the **To date** field.

8.  Select the **Generate file** check box to export the Intrastat report as an XML file or as a CSV file.

9.  In the **File name** field, enter the path and file name where the Intrastat report is exported to.

10. In the **Direction** field, select **Arrivals**, **Dispatches**, or **Both** to indicate the direction of the item transfer.

11. In the **Declaration type** field, select one of the following options as the type of declaration for XML reporting:
    
      - **Primary** – The report that is to be generated is a new report.
    
      - **Null** – The report that is to be generated is a blank report. It is generated for a period that does not contain any transactions.
    
      - **Replacement** – The report that is to be generated is a correction of a previously generated primary report.
    
      - **Deletion** – The report that is to be generated is a cancellation of a previously generated report that was filed.
    

    > [!NOTE]
    > <P>The <STRONG>Declaration type</STRONG> field is available only if you export the Intrastat report as an XML file.</P>



12. Click **OK** to generate and export the Intrastat report as an XML file or as a CSV file.

## See also

[About Intrastat](about-intrastat.md)

[(CZE) Set up a special movement code for Intrastat](cze-set-up-a-special-movement-code-for-intrastat.md)

  


