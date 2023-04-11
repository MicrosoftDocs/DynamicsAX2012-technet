---
title: Deploy language-specific versions of a report
TOCTitle: Deploy language-specific versions of a report
ms:assetid: f9282b61-5a9a-4309-a59e-02883445ab38
ms:mtpsurl: https://technet.microsoft.com/library/Hh496446(v=AX.60)
ms:contentKeyID: 37072028
author: tonyafehr
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Deploy language-specific versions of a report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Typically, when you deploy a report, one version of the report is deployed. This version can then be rendered automatically in every language that is supported by Microsoft Dynamics AX. However, you can configure Microsoft Dynamics AX so that language-specific versions of a report are deployed. A language-specific version of a report is sometimes referred to as a *static version*.

A language-specific version of a report is rendered more quickly for the following reasons:

  - Labels are not resolved at run time.
    

    > [!NOTE]
    > <P>Labels are resolved when you deploy the report. Therefore, if you deploy a report and later change a label, the updated label is not displayed on the report. In this scenario, you must redeploy the report to view the updated label.</P>



  - Columns are not collapsed at run time.


> [!NOTE]
> <P>A language-specific version of a report is designed to render quickly. If you are a developer designing a language-specific version of a report, we recommend that you do not include drill-through links to other reports on the report that you are designing.</P>



## When language-specific versions of reports are deployed

The following table explains when and how language-specific versions of reports are deployed.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Event</p></th>
<th><p>Are language-specific versions deployed?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You select the <strong>Deploy reports</strong> check box when you run the Microsoft Dynamics AX Setup wizard.</p></td>
<td><p>No.</p></td>
</tr>
<tr class="even">
<td><p>While you are completing the Initialization Checklist or the Partition Initialization Checklist, you set up system parameters in the <strong>System parameters</strong> form.</p>
<div class="alert">

> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack, you set up system parameters when you are completing the <EM>Initialization Checklist</EM>. If you are using Microsoft Dynamics AX 2012 R2 or later, you set up system parameters when you are completing the <EM>Partition Initialization Checklist</EM>.</P>


</div></td>
<td><p>No.</p>
<p>However, at this point, the <strong>Report deployment settings</strong> form is populated with a list of reports for which we recommend that you deploy language-specific versions. This list includes the following reports:</p>
<ul>
<li><p>FreeTextInvoice</p></li>
<li><p>ProdPickList</p></li>
<li><p>ProdRouteCard</p></li>
<li><p>PurchPackingSlip</p></li>
<li><p>PurchPurchaseOrder</p></li>
<li><p>PurchReceiptsList</p></li>
<li><p>SalesConfirm</p></li>
<li><p>SalesInvoice</p></li>
<li><p>SalesPackingSlip</p></li>
<li><p>SalesQuotation</p></li>
<li><p>SalesQuotationConfirmation</p></li>
<li><p>VendInvoiceDocument</p></li>
<li><p>WMSBillOfLading</p></li>
<li><p>WMSPickingList_OrderPick</p></li>
</ul>
<p>The next time that you deploy or redeploy these reports, language-specific versions are deployed.</p></td>
</tr>
<tr class="odd">
<td><p>You redeploy all reports by using Windows PowerShell.</p></td>
<td><p>Yes.</p>
<p>Language-specific versions are deployed for each report for which the <strong>Use static report design</strong> check box is selected in the <strong>Report deployment settings</strong> form.</p></td>
</tr>
</tbody>
</table>


## Deploy language-specific versions of a report

To deploy language-specific versions of a report, complete the following procedure.

1.  Open Microsoft Dynamics AX.

2.  Click **System administration** \> **Setup** \> **Business intelligence** \> **Reporting Services** \> **Report deployment settings**.

3.  Click **New**.

4.  In the **Report name** field, select the report for which you want to deploy language-specific versions.

5.  In the **Report design name** field, select a report design.

6.  Select the **Use static report design** check box.

7.  Close the **Report deployment settings** form.

8.  Deploy the report by following the instructions in [Deploy the default reports](deploy-the-default-reports.md). A language-specific version of the report is deployed for each language that is enabled in your Microsoft Dynamics AX installation.
    
    If Reporting Services is running in native mode, the language-specific versions are deployed to the DynamicsAX\\StaticReports folder on the Report Manager website.
    
    If Reporting Services is running in SharePoint integrated mode, the language-specific versions are deployed to the StaticReports folder in the document library that stores all of your Microsoft Dynamics AX reports.

  


