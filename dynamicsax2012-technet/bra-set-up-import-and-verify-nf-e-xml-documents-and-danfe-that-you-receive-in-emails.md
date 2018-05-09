---
title: (BRA) Set up, import, and verify NF-e XML documents and DANFE that you receive in emails
TOCTitle: (BRA) Set up, import, and verify NF-e XML documents and DANFE that you receive in emails
ms:assetid: 1ddf4c84-168e-45b1-a2a7-407b784dfcf8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn479042(v=AX.60)
ms:contentKeyID: 59632410
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- XML
- Forms.SysOperationTemplateForm
- Forms.LogisticsAddressSetup
- Brazil
- Forms.FiscalDocument_BR
- Forms.EFDocParameters_BR
- DANFE
- Forms.EFDocEmailAccountConfiguration_BR
- Forms.EFDocReceivedXmlPendingActions_BR
- Forms.EFDocumentReceivedXML_BR
- BR - 00048
- emails
- NF-e XML
- import XML
- import DANFE
- import NF-e XML
- verify DANFE
- verify XML
---

# (BRA) Set up, import, and verify NF-e XML documents and DANFE that you receive in emails 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to set up and use Microsoft Dynamics AX to import Nota Fiscal eletrônica (NF-e) XML documents and Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) that you receive in emails. For more information, see [(BRA) Import and verify NF-e XML documents and DANFE that you receive in emails](bra-import-and-verify-nf-e-xml-documents-and-danfe-that-you-receive-in-emails.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Brazil</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Set up web services and schemas for a domain. Set up web services that are related to a fiscal authority. For more information, see <a href="bra-set-up-nf-e-federal-parameters.md">(BRA) Set up NF-e federal parameters</a>.</p></li>
<li><p>Set up an environment, NF-e version, and authority for each fiscal establishment. For more information, see <a href="bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md">(BRA) Set up NF-e parameters for a fiscal establishment</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up email accounts to import XML files and DANFE for NF-e

Use the **Email accounts** form to set up email accounts that are used to import XML documents and DANFE for NF-e.

To perform this task, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Configure email accounts**.

2.  In the **Email accounts** form, click **New** or press CTRL+N to create a new record, and then specify the server address, port, user name, and password for the email account.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Server address</strong></p></td>
    <td><p>Enter the POP3 server address for the email account.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Port</strong></p></td>
    <td><p>Enter the port number to use for the email server.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Require SSL</strong></p></td>
    <td><p>Select this check box to indicate that the server requires a Secure Socket Layer (SSL) encrypted connection.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Username</strong></p></td>
    <td><p>Enter the user name for the email account.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Password</strong></p></td>
    <td><p>Enter the password for the email account.</p></td>
    </tr>
    </tbody>
    </table>


3.  Repeat step 2 to set up additional email accounts.

## 2\. Set up the IBGE code for a state, and then assign the state to an NF-e authority

Use the **Address setup** form to set up the Instituto Brasileiro de Geografia e Estatistica (IBGE) code for a state, and then use the **NF-e federal parameters** form to assign the state to an NF-e authority.

To perform this task, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**.

2.  Click **State/province**, and then in the **State/province** area, select or create a state record. For more information, see “Set up state/province information” in [Key tasks: Set up address formats](key-tasks-set-up-address-formats.md).

3.  In the **IBGE code** field, enter the IBGE code for the state, and then close the form.

4.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e federal parameters**.

5.  Select or create an NF-e authority record. For more information, see “Set up web services for an NF-e” in [(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md).

6.  In the lower pane, on the **States using authority** tab, in the **State** field, select a state for the NF-e authority. The description of the state is updated in the **Description** field.
    

    > [!NOTE]
    > <P>You can only select the states for which you specify the IBGE codes.</P>



## 3\. Import and verify the NF-e XML files and DANFE from emails

Use the **Import XML files from email** form to import the XML files and DANFE for NF-e from emails. You can then use the **Received NF-e XML documents** form to verify the XML document and DANFE for an NF-e and inquire about the current status of the NF-e at the Secretaria da Fazenda (SEFAZ) using the access key.

To import and verify the NF-e XML files and DANFE from emails, follow these steps:

1.  Click **Accounts payable** \> **Periodic** \> **NF-e Federal** \> **Import XML files from email**.

2.  Specify criteria, such as batch group and recurrence schedule, to import the XML files and DANFE.

3.  Click **OK** to import the files from emails.

4.  Click **Accounts payable** \> **Periodic** \> **NF-e Federal** \> **Received NF-e xml documents**.

5.  In the **Received NF-e XML documents** form, verify the access key, fiscal establishment, series, number, Cadastro Nacional da Pessoa Jurídica (CNPJ), and name for the received NF-e XML document.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Access key</strong></p></td>
    <td><p>The access key for the NF-e.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fiscal establishment</strong></p></td>
    <td><p>The fiscal establishment that the NF-e is issued for.</p>
    <div class="alert">

    > [!NOTE]
    > <P>Only the NF-e XML documents that are issued to the CNPJ of the fiscal establishments of the legal entity are imported from the emails.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Series</strong></p></td>
    <td><p>The series number of the NF-e.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number</strong></p></td>
    <td><p>The number of the fiscal document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>CNPJ</strong></p></td>
    <td><p>The taxpayer registration number of the account that issued the NF-e.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the account that issued the NF-e.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is left blank if an account that has the CNPJ of the NF-e issuer is not available in Microsoft Dynamics AX.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>IBGE code</strong></p></td>
    <td><p>The IBGE code for the state where the NF-e is issued.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Status from SEFAZ</strong></p></td>
    <td><p>The last queried status of the NF-e at the SEFAZ.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Date and time of the last inquiry</strong></p></td>
    <td><p>The date and time of the last queried status of the NF-e at the SEFAZ.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Posted</strong></p></td>
    <td><p>A selected check box indicates that the NF-e is posted.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Return Code</strong></p></td>
    <td><p>The return code for the NF-e from the SEFAZ.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>The description of the return code for the NF-e.</p></td>
    </tr>
    </tbody>
    </table>


6.  Select a line, and then on the **Action Pane**, click **XML document** to view the XML file for the NF-e. Close the form.

7.  In the **Received NF-e XML documents** form, select a line, and then on the **Action Pane**, click **DANFE** to view the DANFE for the NF-e. Close the form.

8.  In the **Received NF-e XML documents** form, select a line, and then click **Inquire status** to inquire about the current status of the NF-e at the SEFAZ using the access key. The status, date, and time of the inquiry are updated in the **Status from SEFAZ** and **Date and time of the last inquiry** fields.

You can click **XML document** and **DANFE** on the **Received NF-e federal** tab on the **Action Pane** in the **Fiscal document** form to view the XML document and DANFE for an NF-e. For more information about how to verify the posted fiscal documents, see [(BRA) Fiscal document (form)](https://technet.microsoft.com/en-us/library/jj710548\(v=ax.60\)).

## 4\. Inquire about the status of NF-e access keys at the SEFAZ

Use the **Received XML Inquiry** form to set up Microsoft Dynamics AX to inquire about the status of NF-e access keys at the SEFAZ. Inquiries regarding the status of the NF-e are made multiple times before the NF-e is approved, and one additional inquiry is made about the status after the time that the vendor has to cancel an approved NF-e has elapsed.

To inquire about the status of NF-e access keys at the SEFAZ, follow these steps:

1.  Click **Accounts payable** \> **Periodic** \> **NF-e Federal** \> **Inquire about NF-e access key status**.

2.  In the **Limit of cancellation** field, enter the number of hours that the vendor has to cancel the NF-e.

3.  In the **Minimum inquiry interval** field, enter the minimum interval between the inquiries in minutes for the received NF-e access key at the SEFAZ.

4.  You can specify the additional batch processing criteria, such as batch group and recurrence schedule, on the **Batch** tab, and then click **OK**. For more information about batch processing, see [Batch processing overview](batch-processing-overview.md)

## 5\. Update access keys or XML documents for posted electronic fiscal documents

Use the **Posted NF-e with pending validation** form to view the posted electronic fiscal documents for which the access keys or XML documents are not available in the **Received NF-e XML documents** form. You can then update the access keys or XML documents for the electronic fiscal documents after posting.

To perform this task, follow these steps:

1.  Click **Accounts payable** \> **Periodic** \> **NF-e Federal** \> **Posted NF-e with pending validation**.

2.  In the **Posted NF-e with pending validation** form, select one of the following check boxes to filter the list of NF-e documents that are displayed in the form:
    
      - Select the **SEFAZ status not inquired** check box to view a list of NF-e documents for which the access keys are not validated by the SEFAZ. You can validate the access keys for these NF-e documents after posting.
    
      - Select the **Fiscal document status differs from SEFAZ status** check box to view a list of NF-e documents for which the status is updated from approved to canceled. You can cancel these NF-e documents and create and post the corrected NF-e documents. For more information, see [(BRA) Cancel a vendor NF-e](bra-cancel-a-vendor-nf-e.md), [(BRA) Post an NF-e from a purchase order](bra-post-an-nf-e-from-a-purchase-order.md), and [(BRA) Post an NF-e from a tax fiscal document](bra-post-an-nf-e-from-a-tax-fiscal-document.md).
    
      - Select the **NF-e documents that do not have XML attachments** check box to view a list of NF-e documents for which XML attachments are not available. You can import NF-e XML documents from an email for these NF-e documents after posting. For more information, see 3. Import and verify the NF-e XML files and DANFE from emails.
    
      - Select the **Access keys are not found in received NF-e XML documents** check box to view a list of NF-e documents for which the access keys are not available in received NF-e XML documents. You can enter the access keys for these NF-e documents manually in the **Received NF-e XML documents** form. For more information, see 3. Import and verify the NF-e XML files and DANFE from emails.

## Related tasks

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.


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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up, import, and verify NF-e XML documents, you must be a member of a security role that includes the duties that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable receipt electronic fiscal document process</strong></p></td>
<td><p>EFDocumentReceivedXMLEnable_BR</p></td>
<td><p>Set up email accounts to import XML files and DANFE for NF-e</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain electronic fiscal document received</strong></p></td>
<td><p>EFDocumentReceivedXMLMaintain_BR</p></td>
<td><ul>
<li><p>Set up email accounts to import XML files and DANFE for NF-e</p></li>
<li><p>Import and verify the NF-e XML files and DANFE from emails</p></li>
<li><p>Update access keys or XML documents for posted electronic fiscal documents</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Inquire into receipt electronic fiscal documents</strong></p></td>
<td><p>EFDocumentReceivedXMLInquire_BR</p></td>
<td><p>Inquire about the status of NF-e access keys at the SEFAZ</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up, import, and verify NF-e XML documents, you must be a member of a security role that includes the privileges that are described in the following table:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable receipt electronic fiscal document process</strong></p></td>
<td><p>EFDocumentReceivedXMLEnable_BR</p></td>
<td><p>Set up email accounts to import XML files and DANFE for NF-e</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain access key for validation of electronic fiscal document</strong></p></td>
<td><p>EFDocumentReceivedXMLMaintain_BR</p></td>
<td><ul>
<li><p>Set up email accounts to import XML files and DANFE for NF-e</p></li>
<li><p>Import and verify the NF-e XML files and DANFE from emails</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>View access key and xml of electronic fiscal document received</strong></p></td>
<td><p>EFDocumentReceivedXMLView_BR</p></td>
<td><ul>
<li><p>Import and verify the NF-e XML files and DANFE from emails</p></li>
<li><p>Inquire about the status of NF-e access keys at the SEFAZ</p></li>
</ul></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

