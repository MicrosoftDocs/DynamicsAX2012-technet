---
title: (BRA) Generate emails for approved NF-e and attach DANFE PDF files and NF-e XML files to the emails
TOCTitle: (BRA) Generate emails for approved NF-e and attach DANFE PDF files and NF-e XML files to the emails
ms:assetid: b2fad424-f518-422d-a4d9-eb81881a37a7
ms:mtpsurl: https://technet.microsoft.com/library/Dn527711(v=AX.60)
ms:contentKeyID: 59626282
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- XML
- email
- Brazil
- electronic fiscal document
- Classes.EFDocEmailProcess_BR
- BR - 00045
- emails
- NF-e XML
- DANFE PDF
- electronic fiscal documents
- approved NF-e
- generate email
- NF-e emails
- Generate emails
- NF-e email
audience: Application User
ms.search.region: Brazil
---

# (BRA) Generate emails for approved NF-e and attach DANFE PDF files and NF-e XML files to the emails 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) for a Nota Fiscal eletrônica (NF-e) as a PDF file. You can then send the DANFE PDF file and the NF-e XML file that are generated for an approved NF-e to a third-party customer or vendor via email. You must set up an email template before you can generate emails for approved electronic fiscal documents. For more information, see [(BRA) Set up email parameters and email templates for an NF-e](bra-set-up-email-parameters-and-email-templates-for-an-nf-e.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



Use this procedure to generate emails for approved electronic fiscal documents and attach DANFE PDF files and NF-e XML files to the emails.

1.  Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **Generate emails for NF-e**.

2.  Select the **Batch processing** check box to run batch processing.

3.  In the **Task description** field, enter a description for the batch job.

4.  In the **Batch group** field, select the batch group for the batch job.

5.  Select the **Private** check box to restrict other users from running this batch job. A private batch job can be run only by the user who creates it, and only on the computer that the user is logged on to.

6.  Click **Recurrence** to open the **Recurrence** form, where you can specify the recurrence schedule of the batch job, if required. For example, you can set up a batch job to run every second Tuesday. Click **OK**.

7.  Click **Alerts** to open the **Set up alerts for batch jobs** form, where you can set up alerts for the batch job, if required. Click **OK**.

8.  Click **OK** to set up and run the batch job to generate emails for approved electronic fiscal documents and add the emails to the queue for email batch processing. The NF-e XML files are attached to the emails.
    

    > [!NOTE]
    > <P>The DANFE PDF files are attached to emails that are generated for issued electronic fiscal documents if you select the <STRONG>Attach the DANFE as PDF file to email</STRONG> check box on the <STRONG>NF-e federal</STRONG> FastTab in the <STRONG>Fiscal establishments</STRONG> form.</P>



9.  Run the email batch process to send the emails to the third-party customers or vendors. For more information, see [E-mail distributor batch (form)](https://technet.microsoft.com/library/bb147537\(v=ax.60\)) and [Batch processing overview](batch-processing-overview.md).

You can check the status of the emails for approved electronic fiscal documents in the **NF-e email status** form. Click **Accounts receivable** \> **Periodic** \> **NF-e Federal** \> **NF-e email status**.

## See also

[(BRA) Generate DANFE as PDF files](bra-generate-danfe-as-pdf-files.md)

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  


