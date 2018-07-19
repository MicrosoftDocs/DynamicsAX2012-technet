---
title: (RUS) View, reverse, or print electronic reporting documents
TOCTitle: (RUS) View, reverse, or print electronic reporting documents
ms:assetid: 1d2218f9-f295-4784-b735-a7b213e9229a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677473(v=AX.60)
ms:contentKeyID: 49384777
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reverse
- documents
- electronic reporting
- print document
audience: Application User
ms.search.region: Russia
---

# (RUS) View, reverse, or print electronic reporting documents 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Version** form to view, reverse, or print an electronic reporting document.

1.  Click **General ledger** \> **Reports** \> **External** \> **Electronic documents list**.

2.  To open the document in Microsoft Excel, select a document that has a status of **Received**, **Approved**, or **Finished**, and then click **View**. The Excel worksheet is opened on the **Document** tab.
    

    > [!NOTE]
    > <P>If the worksheet opens in a new window, you must update the system register to open the worksheet in the lower pane of the form. For more information, see <A href="rus-update-the-system-register-for-electronic-reporting.md">(RUS) Update the system register for electronic reporting</A>.</P>



3.  To print the current version of the document, click **Print** \> **Print**.
    
    –or–
    
    To open the current version of the document in an Excel worksheet, click **Print** \> **Open Microsoft Excel**.

4.  To compare document versions, click **Functions** \> **Compare**.
    
    –or–
    
    To verify that the values of requisites and sections in the selected version of the document are correct, click **Functions** \> **Check**.

5.  To reverse any changes that were made to the document, click **Functions** \> **Cancel**.
    

    > [!NOTE]
    > <P>The <STRONG>Cancel</STRONG> option is available only after you click <STRONG>Functions</STRONG> &gt; <STRONG>Compare</STRONG> or <STRONG>Functions</STRONG> &gt; <STRONG>Check</STRONG>.</P>



6.  To view the change history of a requisite, on the **Requisites** tab, select the requisite, and then click **Inquiries** \> **Data**.

7.  In the **Data** form, click the **Report lines** tab to view the value on the financial report line that corresponds to the selected requisite.
    

    > [!NOTE]
    > <P>The <STRONG>Report lines</STRONG> tab is available only if the document version is opened by clicking <STRONG>Load</STRONG> &gt; <STRONG>Report</STRONG> in the <STRONG>Documents</STRONG> form.</P>



8.  On the **Report lines** tab, double-click the **Value** field on the selected line to view ledger transactions that are used to calculate the requisite.

## See also

[(RUS) Update an electronic reporting document](rus-update-an-electronic-reporting-document.md)

[(RUS) Documents (form)](https://technet.microsoft.com/en-us/library/jj852139\(v=ax.60\))

[(RUS) Version (form)](https://technet.microsoft.com/en-us/library/jj710759\(v=ax.60\))

[(RUS) Versions (form)](https://technet.microsoft.com/en-us/library/jj710762\(v=ax.60\))

  


