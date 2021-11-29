---
title: Set up an outbound payment format
TOCTitle: Set up an outbound payment format
ms:assetid: 325b86ae-7aca-4f86-beec-a5d507b4a81b
ms:mtpsurl: https://technet.microsoft.com/library/Hh208576(v=AX.60)
ms:contentKeyID: 36056360
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payments
- vendor payment
audience: Application User
ms.search.region: Global
---

# Set up an outbound payment format 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create electronic payments by using payment formats that work with Application Integration Framework (AIF) services. Use this procedure to set up an outbound payment format. The resulting payment format can be selected in the **Payment format** field in the **Generate payments** form when you create electronic payments.

## Prerequisites

Before you begin, a system administrator must follow these steps:

1.  Create a folder for the XML style sheet, such as c:\\AX\\SEPA.

2.  Export the XML style sheet for the payment format from the Application Object Tree (AOT), or create a custom payment format and style sheet. Save the XSL file in the folder that was created, such as c:\\AX\\SEPA\\SEPAVend.xsl.

3.  Set up a batch job to generate electronic payments for the payment format.

For information about these prerequisites, see [Walkthrough: Configuring an outbound integration port for payments](walkthrough-configuring-an-outbound-integration-port-for-payments.md).

## Set up an outbound payment format

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Electronic payment services** \> **Outbound ports for electronic payments**.

2.  Click **New** and enter a name for the payment format. This name will be displayed in the **Payment format** list in the **Generate payments** form when you create electronic payments.

3.  Select the outbound port name. The options in the list are specified in the **Outbound ports** form.

4.  Select the style sheet for the payment format, such as c:\\AX\\SEPA\\SEPAVend.xsl.

5.  Select the folder location where the electronic payment files should be generated.
    

    > [!IMPORTANT]
    > <P>All users who will generate electronic payments for the payment format must have Write access to this folder.</P>



6.  Click **Create ports**.

7.  Click **Payment processing data**.

8.  Enter a value for each line that is displayed in the **Payment processing data** form. The lines that are shown in the form depend on the payment format that is used.

9.  Click **OK** in the **Payment processing data** and then close the **Outbound ports for electronic payments** form.

## See also

[Walkthrough: Configuring an outbound integration port for payments](walkthrough-configuring-an-outbound-integration-port-for-payments.md)

[Payment processing data (form)](https://technet.microsoft.com/library/hh242773\(v=ax.60\))

[Outbound ports for electronic payments (form)](https://technet.microsoft.com/library/hh208616\(v=ax.60\))

  


