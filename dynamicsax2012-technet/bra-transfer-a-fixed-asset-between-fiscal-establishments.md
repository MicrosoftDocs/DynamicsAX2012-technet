---
title: (BRA) Transfer a fixed asset between fiscal establishments
TOCTitle: (BRA) Transfer a fixed asset between fiscal establishments
ms:assetid: c5507b2b-5d30-4839-9879-a0142cdafa40
ms:mtpsurl: https://technet.microsoft.com/library/Dn305883(v=AX.60)
ms:contentKeyID: 54912980
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Transfer a fixed asset between fiscal establishments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When a fixed asset that has a CIAP fixed asset record is transferred from one fiscal establishment to another within the same legal entity, the CIAP accumulation must end in the original fiscal establishment, and a new CIAP fixed asset accumulation must start in the new fiscal establishment. When the new CIAP fixed asset starts, it will start with the remaining Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) amount and the remaining number of installments.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>




> [!NOTE]
> <P>For more information about fiscal establishments, see <A href="bra-about-fiscal-establishments.md">(BRA) About fiscal establishments</A>.</P>



## Transfer a fixed asset

To transfer a fixed asset between fiscal establishments, a free text invoice must be created in the original fiscal establishment and a purchase order must be created in the destination fiscal establishment.


> [!NOTE]
> <P>The fiscal establishment that receives the ICMS tax credit or debit must be set up as a customer or vendor.</P>



## Create a free text invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, on the **Invoice** tab, click **Free text invoice** to create a free text invoice. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

3.  In the **Free text invoice** form, on the **Action Pane**, on the **Invoice** tab, click **Header view**.

4.  In the **Fiscal establishment ID** field, select the identification code for the destination fiscal establishment.

5.  Click the **Fiscal information** FastTab, and then in the **Fiscal document type** and **Operation type** fields, select the type of fiscal document and type of operation for the transaction. The operation type determines whether the customer invoice affects inventory, ledger, customer, or remittance transactions.
    

    > [!NOTE]
    > <P>The fixed asset remains in the original legal entity; the operation type selected should not create financial transactions.</P>



6.  Select the **Final user** check box if the customer is the final user. If this check box is selected, the ICMS tax base includes the Imposto Sobre Produtos Industrializados (IPI) tax and any freight charges.

7.  On the **Action Pane**, on the **Invoice** tab, click **Fiscal document texts** to open the **Fiscal document text** form, where you can attach fiscal document texts to the invoice. For more information, see [(BRA) Attach fiscal document texts to a free text invoice](bra-attach-fiscal-document-texts-to-a-free-text-invoice.md).
    
    On the **Fiscal document text** form, enter the remaining CIAP ICMS tax credit information and the number of installments.

8.  On the **Action Pane**, on the **Invoice** tab, click **Post** to open the **Post free text invoice** form.

9.  Click the **Bill of lading** tab, and then in the **Volume type** and **Volume quantity** fields, enter the volume type and volume quantity that are used in an invoice posting.
    

    > [!NOTE]
    > <P>The <STRONG>Bill of lading</STRONG> tab is available only if the <STRONG>Service invoice</STRONG> check box is not selected on the <STRONG>Fiscal information invoice line</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Free text invoice</STRONG> form.</P>



10. Click **OK** to post the free text invoice.

## Create a purchase order

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**, and then in the **Vendor account** field, select a vendor account.

3.  On the **General** FastTab, in the **Purchase type** field, select **Purchase order**.

4.  Click **OK**.

5.  In the **Purchase order** form, create a purchase order line. At a minimum, you must specify an item, a purchase quantity, a unit, and a unit price.

6.  On the **Line details** FastTab, on the **Product** tab, in the **Site** field, select a site.

7.  On the **Action Pane**, click **Fiscal document texts** to attach fiscal document texts to the purchase order. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).
    
    Enter the fixed asset number in the **Fiscal document texts** form.

8.  On the **Action Pane**, click **Invoice** \> **Invoice**.

9.  In the **Vendor invoice** form, enter values in the **Number**, **Invoice description**, and **Series** fields. For more information, see [(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\)).

10. Click **Post** \> **Post** to post the invoice.

  


