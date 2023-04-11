---
title: (NOR) Configure EHF electronic invoicing
TOCTitle: (NOR) Configure EHF electronic invoicing
ms:assetid: 935781c9-0825-47ce-8749-60dd1db42807
ms:mtpsurl: https://technet.microsoft.com/library/Dn304982(v=AX.60)
ms:contentKeyID: 54899958
author: tonyafehr
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.BatchGroup
- Forms.BatchJob
- Forms.AifEndpointActionValueMap
- Forms.SysRecurrence
- Forms.AifOutboundPort
- Forms.Batch
- Forms.AifPortActionPolicy
- Forms.CustTable
- NO - 00010
- NO - 00009
audience: Application User
ms.search.region: Norway
---

# (NOR) Configure EHF electronic invoicing 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Before you can generate Elektronisk HandelsFormat (EHF) electronic documents, you must configure EHF electronic invoicing. Follow the steps in this topic to configure Microsoft Dynamics AX for EHF electronic invoicing, and then set up customer accounts for EHF electronic invoicing, Application Integration Framework (AIF), batch groups, batch processing, and recurring batch jobs.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 4 for AX 2012.</P>



The following illustration shows how to configure EHF electronic invoicing. The numbers correspond to the procedures later in this topic.

![Configure EHF electronic invoicing](images/Dn304982.CU4-Norway-(AX.60).gif "Configure EHF electronic invoicing")

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Set up a legal entity in the <strong>Legal entities</strong> form. For more information, see <a href="create-or-modify-a-legal-entity.md">Create or modify a legal entity</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up the country or region and the International Organization for Standardization (ISO) code in the <strong>Address setup</strong> form. ISO codes are used for electronic invoicing. For more information, see <a href="key-tasks-set-up-address-formats.md">Key tasks: Set up address formats</a>.</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>Define a three character ISO currency code for each of the currencies in the <strong>Currencies</strong> form. This ISO code is used for electronic invoicing. For more information, see <a href="create-a-currency-code.md">Create a currency code</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up exchange rates in the <strong>Currency exchange rates</strong> form. Verify that the ISO currency code for the currency code that is used for electronic invoicing (for example, NOK for Norwegian krone) complies with the three-character ISO standard. For more information, see <a href="https://technet.microsoft.com/library/hh209477(v=ax.60)">Currency exchange rates (form)</a>.</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>Set up sales tax codes for electronic invoices in the <strong>Sales tax codes</strong> form. For more information, see <a href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up job titles in the <strong>Contact person titles</strong> form. For more information, see <a href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</a>.</p></td>
</tr>
<tr class="odd">
<td></td>
<td><p>Set up inventory units by specifying external codes according to the United Nations Center for Trade Facilitation and Electronic Business Information Content Management Group (UN/CEFACT ICG) standards in the <strong>Units</strong> form. For more information, see <a href="https://technet.microsoft.com/library/hh209233(v=ax.60)">Units (form)</a> and <a href="https://technet.microsoft.com/library/aa583814(v=ax.60)">External codes (form)</a>.</p></td>
</tr>
<tr class="even">
<td></td>
<td><p>Set up an enhanced integration port. For more information, go to <a href="create-edit-or-delete-an-enhanced-integration-port.md">Create, edit, or delete an enhanced integration port</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Configure Microsoft Dynamics AX for EHF electronic invoicing

The electronic invoices that you generate include required information, such as the contact person, invoice number, and address information. Microsoft Dynamics AX applies validation rules when invoices are generated so that you can verify that the correct information is entered. If you find errors, you can correct the errors before you submit the invoices.

You must set up folders where you can save the error messages, the XML files, and the EHF files. Microsoft Dynamics AX uses these folders to store source documents, processed documents, Extensible Stylesheet Language for Transformations (XSLT) files, and the error messages that are generated when the XML file is converted to EHF format. You can specify these folders when you set up AIF and set up the batch job for EHF electronic invoicing. For more information, see 3. Set up AIF for EHF electronic invoicing and 5. Set up batch processing for EHF electronic invoicing.

To configure Microsoft Dynamics AX for EHF electronic invoicing, set up the following folder structure in a shared location that is accessible from the Application Object Server (AOS) computer and from any client computers that are used as batch servers in your system.

  - \\\\Server\\EHF\\Sales\\Error – Used to save error messages that are generated when the XML file is converted to the EHF format.

  - \\\\Server\\EHF\\Sales\\Processed files – Used to save documents after they are processed. The documents are moved from the Target folder to this folder.

  - \\\\Server\\EHF\\Sales\\Source – Used to save the XML file that is generated by Microsoft Dynamics AX.

  - \\\\Server\\EHF\\Sales\\Target – Used to save the EHF file after the XML file has been processed.

  - \\\\Server\\EHF\\Sales\\XSLT – Used to contain the XSLT schema file for collection letters.

## 2\. Set up customer accounts for EHF electronic invoicing

Use the **Customers** form to specify the address and contact details for each company that you generate electronic invoices for. You can create contacts in the **Contacts** form and assign a contact to a customer account. The contact information is included when you generate an electronic invoice for a customer. For more information, see [Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\)).

To set up a customer account for EHF electronic invoicing, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account, or on the **Action Pane**, click **Customer** to create a customer account. For more information, see [Create a customer record](create-a-customer-record.md).

3.  In the **Customers** form, click **Edit**, and then click the **Addresses** FastTab to verify that the country or region code, ZIP or postal code, and the street name are entered for the primary address.

4.  Click the **Invoice and delivery** FastTab, and then select the **eInvoice** check box to use electronic invoicing for customer transactions.

5.  On the **Action Pane**, on the **Customer** tab, click **Contacts**, and then click **Add contacts** to open the **Contacts** form.

6.  Create a contact for the selected customer. For more information, see [Contacts (form)](https://technet.microsoft.com/library/aa574743\(v=ax.60\)).

## 3\. Set up AIF for EHF electronic invoicing

Use the **Outbound ports** form to create an outbound port; set up services and adapters for an outbound port, and specify the AIF settings that are required to generate EHF electronic invoices.

You must scan for new adapters and services before you configure outbound ports for the first time. The port configuration is affected when there is a change in the Application Object Tree (AOT). You must also scan the adapters and services every time that a change that affects the port configuration is made to the AOT.

For information about how to configure the enhanced integration port, go to [Managing integration ports](managing-integration-ports.md).

To set up AIF for EHF electronic invoicing, follow these steps:

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  Create an outbound port, and then in the **Port name** and **Description** fields, enter a name and a description for the outbound port.

3.  In the **Adapter** field, select **File system adapter**. This adapter is used to create and save the EHF electronic invoices or collection letters.

4.  In the **URI** field, specify the Uniform resource identifier (URI) of the Source folder to save the sales invoices. For more information, see 1. Configure MSDAX for EHF electronic invoicing.

5.  On the **Service contract customizations** FastTab, click **Service operations**. In the **Select service operations** form, select the **CustCollectionLetterService\_NO.read** service operation for sales invoices, and move it to the **Selected service operations** list. Close the form.

6.  In the **Outbound ports** form, select the **Customize documents** check box, and then click **Data policies**.

7.  In the **Document data policies** form, click **Enable all** to select all XML schema elements, and then close the form.

8.  On the **Processing options** FastTab, in the **Default encoding format** field, select **UTF-8**.

9.  Select the **Apply value mapping** check box, and then click **Value mapping** to open the **Value mapping** form, where you can map the values such as item number, customer account number, vendor account number, terms of delivery, and unit for the outbound port. Close the form.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: You must indicate the unit for which you specified the external code according to the UN/CEFACT ICG standards. For more information, see Prerequisites.</P>



10. On the **Troubleshooting** FastTab, in the **Logging mode** field, select **All document versions**.

11. Optional: Select the **Include exceptions in fault** check box to display the X++ error messages.

12. Optional: On the **Security** FastTab, in the **Restrict to company** field, select the company that the electronic invoices are generated for.

13. Click **Activate** to use the port to exchange data by using AIF.

## 4\. Set up a batch group for EHF electronic invoicing

Use the **Batch group** form to set up a batch group to process the EHF electronic invoices.

To set up a batch group for EHF electronic invoicing, follow these steps:

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Create a batch group to process the customer invoices. For more information, go to [Create a batch group](create-a-batch-group.md).

3.  On the **Batch servers** tab, select a server to run the batch job, and then move the server from the **Remaining servers** list to the **Selected servers** list.

## 5\. Set up batch processing for EHF electronic invoicing

Use the **Batch job** form to set up batch processing for EHF electronic invoicing. You can process electronic invoices by using batch jobs. For more information, see [Batch processing overview](batch-processing-overview.md).

To set up a batch job for EHF electronic invoicing, follow these steps:

1.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Press CTRL+N to create a batch job, and then in the **Job description** field, enter a short description for the batch job. For more information, go to [Create a batch job](create-a-batch-job.md).

3.  Save the batch job, and then click **View tasks**.

4.  In the **Batch tasks** form, press CTRL+N to create a batch task for the batch job, and then in the **Company accounts** field, select the company that you created the batch job for.

5.  Create three batch tasks, one for each of the following class names:
    
      - **AifOutboundProcessingService**
    
      - **AifGatewaySendService**
    
      - **EInvoiceFileTransform\_OIOUBL**

6.  Select the batch task that uses the **EInvoiceFileTransform\_OIOUBL** class name, and then in the **Batch group** field, select a batch group.

7.  Click **Refresh** to refresh the data in the form.

8.  Click **Parameters**, and then in the **E-invoice OIOUBL XSL File Transformation** form, specify the locations of the Source, Target, Processed, and Error file storage folders. For the XSLT file path, select the path for the XSLT schema file for sales outbound electronic invoices, and then click **OK**.

9.  In the **Batch tasks** form, on the **Overview** tab, select the batch task that uses the **AifGatewaySendService** class name (the second task) to set up the order that the batch tasks are run for.

10. In the lower pane, press CTRL+N to create a condition for the selected batch task to run after the batch task that uses the **AifOutboundProcessingService** class name (the first task) has ended.

11. In the **Task ID** field, select the batch task that uses the **AifOutboundProcessingService** class name, and then in the **Expected status** field, select **Ended**.
    

    > [!NOTE]
    > <P>You can also select the batch task that uses the <STRONG>EInvoiceFileTransform_OIOUBL</STRONG> class name, and then set the condition to run the batch task when the batch task that uses the <STRONG>AifGatewaySendService</STRONG> class name has ended.</P>



## 6\. Set up recurring batch jobs

Use the **Recurrence** form to set up recurring batch jobs for EHF electronic invoices.

To set up recurring batch jobs, follow these steps:

1.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Select an outbound electronic invoice batch job.

3.  Click **Recurrence**, and in the **Time zone information**, **Range of recurrence**, and **Recurring pattern** field groups, specify your options, and then click **OK**.

4.  In the **Batch job** form, select the batch job, click **Functions** \> **Change status**, and then select **Waiting**.

## Next step

You have finished configuring EHF electronic invoicing. Continue to create an EHF electronic invoice. For more information, see [(NOR) Generate an EHF electronic document for a collection letter](nor-generate-an-ehf-electronic-document-for-a-collection-letter.md).

## Related tasks

[(NOR) EHF electronic documents](nor-ehf-electronic-documents.md)

  


