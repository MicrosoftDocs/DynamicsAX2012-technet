---
title: (BRA) Set up a fiscal document source text
TOCTitle: (BRA) Set up a fiscal document source text
ms:assetid: d6994cef-0af1-419a-a8a5-cc5d0a6c02f5
ms:mtpsurl: https://technet.microsoft.com/library/JJ663937(v=AX.60)
ms:contentKeyID: 49384522
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- fiscal document
- fiscal document source text
- source text
- set up fiscal document source text
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a fiscal document source text 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can attach fiscal document texts to a sales order, purchase order, or free text invoice. The fiscal document texts that are attached to the sales order, purchase order, or free text invoice are printed on the fiscal document. The fiscal document texts provide additional information about the taxes and laws that are applied to the fiscal document. You can also include placeholders in the fiscal document source text. The placeholders are replaced by predefined text when you post the fiscal document that the fiscal document text is attached to. For more information about placeholders, see [(BRA) About fiscal document text placeholders](bra-about-fiscal-document-text-placeholders.md).

You must set up a fiscal document source text before you can attach it to a fiscal document.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal document source texts**.

2.  Create a fiscal document source text.

3.  In the **Text ID** field, enter an identifier for the fiscal document source text.

4.  In the **Description** field, enter a brief description of the fiscal document source text.

5.  In the **Text** field, enter the text that is printed on fiscal documents. You can also include placeholders.
    

    > [!NOTE]
    > <P>The text that you enter in the <STRONG>Text</STRONG> field is the default text for the fiscal document source text. When you attach a fiscal document text to a fiscal document, you can modify the text in the <STRONG>Note</STRONG> field in the <STRONG>Fiscal document texts</STRONG> form.</P>



6.  In the **Restriction** field, select one of the following options to indicate whether the text is printed on the fiscal documents:
    
      - **Internal** – The text is not printed on fiscal documents.
        

        > [!NOTE]
        > <P>If you clear the <STRONG>Fiscal information</STRONG> check box, the text is not posted with the fiscal documents.</P>

    
      - **External** – The text is posted and printed on fiscal documents.

7.  Select the **Fiscal information** check box to update the details of the fiscal document text on electronic fiscal documents. The fiscal document source text is also included in the fiscal book or Sistema Público de Escrituração Digital (SPED).

8.  In the **Process reference** field group, click **New** to add fiscal process information.

9.  In the **Agency** field, select the agency that is related to the fiscal process.

10. In the **Reference process number** field, enter an identification code of the process that the fiscal document refers to.

11. Repeat steps 8 through 10 to set up additional fiscal processes.

## See also

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/library/jj663934\(v=ax.60\))

  


