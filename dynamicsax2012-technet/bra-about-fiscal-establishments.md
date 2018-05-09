---
title: (BRA) About fiscal establishments
TOCTitle: (BRA) About fiscal establishments
ms:assetid: 85a9cf3b-2849-42fb-a82a-3226158aa54a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911269(v=AX.60)
ms:contentKeyID: 52075255
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- fiscal establishments
- BR - 00012
---

# (BRA) About fiscal establishments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create fiscal establishment groups and fiscal establishments. A fiscal establishment is a physical location of a legal entity, such as a subsidiary, branch, plant, distribution center, warehouse, or store, which requires a Cadastro Nacional da Pessoa Jurídica (CNPJ) or Inscrição Estadual (IE) tax registration number. A legal entity can have multiple fiscal establishments. Fiscal establishments issue and receive fiscal documents, and assess and pay taxes.

You can perform the following tasks:

  - Create fiscal establishment groups and fiscal establishments. For more information, see [(BRA) Create a fiscal establishment group](bra-create-a-fiscal-establishment-group.md) and [(BRA) Create a fiscal establishment](bra-create-a-fiscal-establishment.md).

  - Specify a fiscal establishment for a site. The address of the site is updated with the address of the fiscal establishment. For more information, see [(BRA) Create sites](bra-create-sites.md).

  - Set up fiscal document types that indicate what type of fiscal document is used for sales and purchase transactions between fiscal establishments. For more information, see [(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md). You can also assign fiscal document types to customers or vendors. For more information, see [(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md).

  - Specify a tax matrix for a fiscal establishment group. You can select the Código Fiscal de Operações e Prestações (CFOP) code based on the fiscal establishment group. Tax groups are available based on the fiscal establishment group and CFOP code that you select. For more information, see [(BRA) Set up the CFOP matrix](bra-set-up-the-cfop-matrix.md) and [(BRA) Set up a tax matrix](bra-set-up-a-tax-matrix.md).

  - Create and post a sales order by specifying sites for sales order lines. You can select the CFOP codes and fiscal document types for the sales order lines based on the fiscal establishments of the sites. The sales tax groups and item sales tax groups for the sales order lines are updated based on the tax matrixes that are attached to the fiscal establishments of the sites by using fiscal establishment groups. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md) and [(BRA) Create and post a return sales order](bra-create-and-post-a-return-sales-order.md).
    

    > [!NOTE]
    > <P>When you post the sales order, a fiscal document is created for each fiscal establishment.</P>



  - Create and post a free text invoice for a fiscal establishment. You can select the CFOP codes for the free text invoice lines based on the fiscal establishment. The sales tax groups and item sales tax groups for the free text invoice lines are updated based on the tax matrixes that are attached to the fiscal establishments of the sites by using fiscal establishment groups. For more information, see [(BRA) Create and post a free text invoice](bra-create-and-post-a-free-text-invoice.md).

  - Create and post a purchase order by specifying sites that are attached to fiscal establishments for the purchase order lines. The sales tax groups and item sales tax groups for the purchase order lines are updated based on the tax matrixes that are attached to the fiscal establishments of the sites by using fiscal establishment groups. For more information, see [(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md), [(BRA) Create and post a vendor invoice for a nontaxpayer vendor](bra-create-and-post-a-vendor-invoice-for-a-nontaxpayer-vendor.md), and [(BRA) Create and post a return purchase order](bra-create-and-post-a-return-purchase-order.md).
    

    > [!NOTE]
    > <P>When you post the purchase order, an invoice is created for each fiscal establishment.</P>



## See also

[(BRA) Fiscal establishment groups (form)](https://technet.microsoft.com/en-us/library/jj923398\(v=ax.60\))

[(BRA) Fiscal establishments (form)](https://technet.microsoft.com/en-us/library/jj933531\(v=ax.60\))

[(BRA) Sites (modified form)](https://technet.microsoft.com/en-us/library/jj923394\(v=ax.60\))

[(BRA) Fiscal document types (form)](https://technet.microsoft.com/en-us/library/jj710551\(v=ax.60\))

[(BRA) Assign fiscal document types (form)](https://technet.microsoft.com/en-us/library/jj710506\(v=ax.60\))

[(BRA) CFOP matrix (form)](https://technet.microsoft.com/en-us/library/jj933496\(v=ax.60\))

[(BRA) Taxes matrix (form)](https://technet.microsoft.com/en-us/library/jj923368\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

