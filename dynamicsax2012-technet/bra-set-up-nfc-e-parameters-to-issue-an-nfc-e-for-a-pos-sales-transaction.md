---
title: (BRA) Set up NFC-e parameters to issue an NFC-e for a POS sales transaction
TOCTitle: (BRA) Set up NFC-e parameters to issue an NFC-e for a POS sales transaction
ms:assetid: ef4dd189-e5ec-41e4-bb0c-023efc30046d
ms:mtpsurl: https://technet.microsoft.com/library/Dn876576(v=AX.60)
ms:contentKeyID: 63378992
author: tonyafehr
ms.date: 02/27/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up NFC-e parameters to issue an NFC-e for a POS sales transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

A Nota Fiscal Consumidor eletrônica (NFC-e) is an electronic fiscal document that is generated and printed to register the sale of an item to a consumer. This topic explains how to set up the parameters that are required to issue or cancel an NFC-e. After setting up these parameters, you must run a retail scheduler job to synchronize these changes with the POS to be able to complete NFC-e transactions.

## Set up NFC-e parameters for fiscal establishments

Use this procedure to set up NFC-e parameters for fiscal establishments.

To complete this procedure, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal establishments**.

2.  Create a new fiscal establishment, and enter basic information about it. For more information, see [(BRA) Fiscal establishments (form)](https://technet.microsoft.com/library/jj933531\(v=ax.60\)).

3.  Enter the tax identification number of the fiscal establishment in the **CNPJ/CPF** field.

4.  On the **NF-e/NFC-e federal** FastTab, in the **Certificate** field, select the digital certificate that is required to generate an NFC-e.
    

    > [!NOTE]
    > <P>A digital certificate for NFC-e transactions must be installed and available before you can use it to generate NFC-es.</P>



5.  In the **NFC-e web service** field group, in the **Environment** field, select **Testing** or **Production** to indicate whether the NFC-e transaction is completed in a testing environment or a production environment.

6.  In the **The version of the NFC-e feature** field, select the NFC-e version.

7.  In the **Authority** field, select the tax authority that is authorized to reject or approve an NFC-e.

8.  Optional: In the **Approved NFC-e** field, select the email template for an approved NFC-e.

9.  Optional: Select the **Attach the DANFE NFC-e as a PDF file to email** check box to attach the NFC-e DANFE as a PDF file to email.

## Specify the end points for an NFC-e web service

Use this procedure to specify the end points for an NFC-e web service. The web service URL is used to communicate with the tax authority for the authorization of an issued NFC-e.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e federal parameters**.

2.  Create a new authority, and then in the lower pane specify the mode of operation for the NFC-e transaction. For more information about setting parameters for a tax authority, see [(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md).

3.  In the **Web service** field, select the type of XML message that is used to communicate with the authority by using the web service environment address.

4.  In the **Version** field, select the version of the NFC-e.

5.  In the **Internet address** field, enter the address of the web service.

## Specify NFC-e attributes for a POS register

Use this procedure to set up attributes for a POS register to perform NFC-e operations. You can also configure a non-fiscal printer in the POS hardware profile form to print a the DANFE NFC-e without a fiscal printer. For more information, see [POS hardware profile (form)](https://technet.microsoft.com/library/hh580636\(v=ax.60\)).

1.  Click **Retail** \> **Setup** \> **POS** \> **POS registers**.

2.  Create a new register or double-click an existing POS register. For more information, see [POS registers (form)](https://technet.microsoft.com/library/hh597141\(v=ax.60\)) and [Set up registers](set-up-registers.md).

3.  On the **Fiscal information** FastTab, in the **Fiscal operation mode** field, select **NFC-e**. You can select **Fiscal printer** to use the POS register only for fiscal printer operations.

4.  In the **Fiscal document series** field, enter the fiscal document series, which is used to generate the serial number for NFC-es. You cannot enter the same fiscal document series for multiple registers within the same retail store.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>NFC-e</STRONG> in the <STRONG>Fiscal operation mode</STRONG> field.</P>



## Set up receipt profiles for NFCe-s

Use this procedure to set up a receipt profile for NFC-es. You can configure the simplified or detailed DANFE receipt formats for NFC-es.

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Receipt profiles**.

2.  Create a new receipt profile. For more information, see [Set up receipt profiles](set-up-receipt-profiles.md).

3.  On the **General** FastTab, click **Add** to add a receipt format to the profile.

4.  In the **Receipt type** field, select **Simplified DANFE** or **Detailed DANFE**. The **Simplified DANFE** layout does not contain the item details. Only the total item quantity and related fiscal information are displayed.

5.  In the **Receipt format** field, select a receipt format. You can view the selected receipt format by clicking **Designer**.

## Assign info codes for voiding an NFC-e or to issue an NFC-e in contingency mode

Use this procedure to create and assign info codes that indicate the reason for voiding an issued NFC-e or for issuing an NFC-e in contingency mode.

1.  Click **Retail** \> **Setup** \> **Info codes**.

2.  Create info codes and subcodes for NFC-es. Select **Subcode list** as the input type for the info code, and enter a 15-character description for the subcode. For more information about info codes and subcodes, see [Set up info codes](set-up-info-codes.md).

3.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Functionality profiles**.

4.  Create a functionality profile or select an existing functionality profile.

5.  On the **Info codes** FastTab, in the **Contingency reason** field, select the info code that is used to indicate the reason for issuing an NFC-e in contingency mode.

6.  In the **Voiding reason** field, select the info code that is used to indicate the reason for voiding an issued NFC-e.

## Determine the taxation code that is applicable for NFC-es

Taxation is applied to NFC-e sale transaction based on Código FIscal de Operações e Prestações (CFOP) codes. The applicable tax rates are determined by crossing the item sales tax group assigned for the item in the **Released product details** form with the sales tax group selected for the retail store. The taxation code resolved for the tax rates is crossed with the product type specified in the **Released product details** form to determine the CFOP code.

## Optional: Set up number sequences for NFC-es

Use this procedure to specify a value other than the default value that is used to initialize the numbering for the issued NFC-es.

1.  Click **Retail** \> **Periodic** \> **Retail POS redeployment**.

2.  Select a retail store, and then click **Edit POS counters**.

3.  In the **NFC-e** field, enter a value that is used to generate a number sequence for NFC-es.

## Next step

  - After setting up these parameters you can issue and print an NFC-e in POS. For more information, see (BRA) Issue and print DANFE for NFC-es.

  - After issuing and printing an NFC-e in POS, you can calculate and post a statement for the NFC-e and view the details of the posted statement in the **All fiscal documents** form. For more information about creating, calculating, and posting statements POS transactions, see [Create and post a statement](create-and-post-a-statement.md).
    
    1.  Click **Retail** \> **Inquiries** \> **All fiscal documents**.
    
    2.  Select a posted fiscal document, and then click **Totals**, **Voucher**, or **Charges** to view the total taxes and voucher details of the NFC-e. The posted NFC-e can have one of the following statuses
        
          - **Approved** – The NFC-e has been authorized and approved by the tax authority.
        
          - **Canceled** – The NFC-e was voided.
        
          - **Created** – The NFC-e was created in contingency mode.
    
    3.  Optional: On the **NF-e federal**, click **Export PDF** to export the DANFE NFC-e as a PDF file.
    
    4.  Optional: Click **Send e-mail** to send the DANFE NFC-e in an email.

  - Create a tax assessment and generate SPED fiscal files for NFC-e transactions. For more information about preparing the tax assessment, see topics under [(BRA) Setting up fiscal books](bra-setting-up-fiscal-books.md) and [(BRA) Working with fiscal books](bra-working-with-fiscal-books.md).

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>Retail</strong> configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To set up NFC-e parameters to issue an NFC-e, you must be a member of the following security roles:</p>
<ol>
<li><p><strong>Retail operation manager</strong></p></li>
<li><p><strong>Accountant</strong></p></li>
</ol></td>
</tr>
</tbody>
</table>

  


