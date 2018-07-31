---
title: (FRA) Draw and print promissory notes
TOCTitle: (FRA) Draw and print promissory notes
ms:assetid: f1baa78d-66ef-49d3-926c-62d2673ac234
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715989(v=AX.60)
ms:contentKeyID: 62200185
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: France
---

# (FRA) Draw and print promissory notes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can draw and print promissory notes, you must perform the following setup tasks:

  - Set up a promissory note format for a bank account by specifying the following information in the **Promissory note layout** form.
    
    1.  On the **General** tab, in the **Promissory note form** field, select **French**.
    
    2.  On the **Setup** tab, in the **Paper format** field, select a paper format to use for printed promissory notes.
    
    For more information, see [Promissory note layout (form)](https://technet.microsoft.com/en-us/library/aa583563\(v=ax.60\)).

  - Set up parameters, such as posting profiles, methods of payment, and accounts payable parameters, for promissory notes. For more information, see [Set up promissory notes](set-up-promissory-notes.md).

Use this procedure to draw and print promissory notes.

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Draw promissory note journal**.

2.  Select or create a journal. For more information, see [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)).

3.  Click **Lines**, and then select or create a journal line. You can draw a promissory note only when invoices for payments are settled. For more information, see [Journal voucher - Promissory note journal (form)](https://technet.microsoft.com/en-us/library/aa552832\(v=ax.60\)).

4.  On the **Promissory note** tab, in the **Bank account** field, select a bank account that is set up to use the **French** promissory note form.

5.  Click **Functions** \> **Generate payments**.

6.  In the **Method of payment** field, select the method of payment that you set up for promissory notes.

7.  Click **Dialog** to open the **Promissory note document** dialog box.

8.  In the **From** field, enter the number of the first promissory note to generate.

9.  In the **Number of blank promissory note documents** field, enter the total number of promissory notes to generate, and then click **OK**.

10. In the **Generate payments** form, click **OK** to print the promissory note document.

## See also

[Draw a promissory note](draw-a-promissory-note.md)

  


