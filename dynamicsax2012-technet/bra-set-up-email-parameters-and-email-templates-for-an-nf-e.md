---
title: (BRA) Set up email parameters and email templates for an NF-e
TOCTitle: (BRA) Set up email parameters and email templates for an NF-e
ms:assetid: 1d49cdc0-e714-4024-9e92-6c2150e9ee03
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933497(v=AX.60)
ms:contentKeyID: 50935111
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Classes.SysEmailDistributor
- Forms.BatchGroup
- Forms.SysEmailTable
- email templates
- email parameters
- Forms.SysEmailParameters
- BRA
- Brazil
- NF-e
- electronic fiscal document
- Forms.FiscalEstablishment_BR
- BR - 00045
- MsDynAx060.Forms.BatchGroup
- MsDynAx060.Forms.FiscalEstablishment_BR
- MsDynAx060.Forms.SysEmailTable
- MsDynAx060.Forms.SysEmailParameters
---

# (BRA) Set up email parameters and email templates for an NF-e [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to set up email parameters to send a Nota Fiscal eletrônica (NF-e) to a vendor or customer automatically after the NF-e is approved or canceled, or if you generate a correction letter. You can set up a batch group and email templates for an NF-e. You must create separate email templates for an approved NF-e, a canceled NF-e, and a correction letter. You can then create a batch process to send the NF-e by email.


> [!NOTE]
> <P>In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: You can send the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) PDF file and the NF-e XML file that are generated for an approved NF-e to a third-party customer or vendor via email.</P>



1.  Click **System administration** \> **Setup** \> **System** \> **E-mail parameters**.

2.  Enter the required details in the following fields:
    
      - **Outgoing mail server**
    
      - **Local computer name**
    
      - **SMTP port number**
    
      - **User name**
    
      - **Password**

3.  Click **System administration** \> **Setup** \> **Batch group**.

4.  Create a batch group for an NF-e. For more information, see [Create a batch group](create-a-batch-group.md).

5.  Click **Organization administration** \> **Setup** \> **E-mail templates**.

6.  Create an email template for an approved NF-e, a canceled NF-e, and a correction letter. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

7.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal establishments**.

8.  Set up the email templates for a fiscal establishment. For more information, see [(BRA) Set up NF-e parameters for a fiscal establishment](bra-set-up-nf-e-parameters-for-a-fiscal-establishment.md).

9.  In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2: On the **NF-e federal** FastTab, select the **Attach the DANFE as PDF file to email** check box to attach the DANFE as PDF files to emails that are generated for issued electronic fiscal documents. Close the form.

10. Click **System administration** \> **Periodic** \> **E-mail processing** \> **Batch**.

11. In the **Batch group** field, select the batch group for an NF-e, and then click **OK**.

## See also

[E-mail parameters (form)](https://technet.microsoft.com/en-us/library/aa591302\(v=ax.60\))

[Batch groups (form)](https://technet.microsoft.com/en-us/library/aa575384\(v=ax.60\))

[Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md)

[Email templates (form)](https://technet.microsoft.com/en-us/library/aa575327\(v=ax.60\))

[E-mail distributor batch (form)](https://technet.microsoft.com/en-us/library/bb147537\(v=ax.60\))

[Batch processing overview](batch-processing-overview.md)

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

[(BRA) Generate DANFE as PDF files](bra-generate-danfe-as-pdf-files.md)

[(BRA) Generate emails for approved NF-e and attach DANFE PDF files and NF-e XML files to the emails](bra-generate-emails-for-approved-nf-e-and-attach-danfe-pdf-files-and-nf-e-xml-files-to-the-emails.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

