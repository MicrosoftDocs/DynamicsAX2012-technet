---
title: (POL) Create and print a correction note
TOCTitle: (POL) Create and print a correction note
ms:assetid: dba55c58-af0b-45fe-a585-f55f140e6475
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711301(v=AX.60)
ms:contentKeyID: 49387119
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- correction note
- correct vendor document
- Poland correction note
---

# (POL) Create and print a correction note [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A correction note is a document that you can use to notify a vendor about errors in the document header of a purchase document. For example, a vendor may issue a sales document that has an incorrect address or value-added tax (VAT) identification number. You can accept and post the document as a purchase invoice, and then issue a correction note to the vendor later. The correction note should describe the error and provide the correct data.

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**. Select the invoice that contains incorrect data, and then click **Create correction notes.**.

2.  In the **Correction notes** form, in the **Document date** field, enter the transaction date. If you do not enter a date, the current date is used for the posting date.

3.  In the **Correction note** field, enter a unique identification number for the correction note.
    

    > [!NOTE]
    > <P>You can generate correction note numbers automatically by setting up a number sequence code for correction note references. Set up number sequences in the <STRONG>Accounts payable parameters</STRONG> form.</P>



4.  On the **Details** tab, in the **Original text** field, enter the text from the original document that you are correcting.

5.  In the **Corrected text** field, enter the correct text.

6.  Click **Post** to post the document.

7.  Click **Print** to print the report.

## See also

[(POL) Correction notes (form)](https://technet.microsoft.com/en-us/library/jj678138\(v=ax.60\))

[Number sequence overview](number-sequence-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

