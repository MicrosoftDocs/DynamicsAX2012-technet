---
title: (BRA) About posting and printing fiscal document texts
TOCTitle: (BRA) About posting and printing fiscal document texts
ms:assetid: 771ac3e6-c84e-4606-9d0b-0265e7f7bf96
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710537(v=AX.60)
ms:contentKeyID: 49384428
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- legal texts
- posted legal texts
- BR - 00020
audience: Application User
ms.search.region: Brazil
---

# (BRA) About posting and printing fiscal document texts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a fiscal document text, and attach the fiscal document text to a sales order, purchase order, or free text invoice. The fiscal document text is printed on the fiscal document or Documento Auxiliar da Nota Fiscal Eletrônica (DANFE). When you create or attach fiscal document texts, you can include fiscal document text placeholders in them. If a fiscal document text contains placeholders, the predefined tags of the placeholders are replaced by specific values. For more information, see [(BRA) About fiscal document text placeholders](bra-about-fiscal-document-text-placeholders.md).

The **Restriction** and **Fiscal information** fields in the **Fiscal document source texts** form are copied as attributes of the fiscal document texts. These attributes determine how the fiscal document text is printed on a fiscal document or DANFE, and whether the fiscal document text is included in the fiscal book or Sistema Público de Escrituração Digital (SPED). For more information, see [(BRA) Set up a fiscal document source text](bra-set-up-a-fiscal-document-source-text.md)

Header texts appear only one time, even when there are multiple instances of the text. The header text for the fiscal document itself takes priority over other text in the header. The line item text for the order appears only once for each line item with the same item code and CFOP code, and takes priority over other line item text for the same line item.

Follow these steps to post and print a fiscal document text on a fiscal document or DANFE.

1.  Set up a fiscal document source text by using the **Fiscal document source texts** form.

2.  Specify the document type for the fiscal document text before you attach it to a sales order, purchase order, or free text invoice. For more information, see [(BRA) Set up the document type for fiscal document texts](bra-set-up-the-document-type-for-fiscal-document-texts.md).

3.  Attach the fiscal document texts to the sales order, purchase order, or free text invoice by using the **Fiscal document texts** form.

4.  Post the sales order, purchase order, or free text invoice to generate a fiscal document with the fiscal document texts printed on it. The placeholder tags are replaced by their values. The fiscal document text is posted and printed as a header or line, based on the **Restriction** and **Fiscal information** fields in the **Fiscal document source texts** form.

## See also

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/en-us/library/jj663934\(v=ax.60\))

[(BRA) Attach fiscal document texts to a free text invoice](bra-attach-fiscal-document-texts-to-a-free-text-invoice.md)

[(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md)

  


