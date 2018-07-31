---
title: Set up sales tax for the United States
TOCTitle: Set up sales tax for the United States
ms:assetid: 77fe630e-dd16-473c-a0c0-9ce0779553eb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550046(v=AX.60)
ms:contentKeyID: 36058217
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- U. S. sales tax
- U.S. sales tax
- United States sales tax
audience: Application User
ms.search.region: Global
---

# Set up sales tax for the United States 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following steps describe how to set up sales for the United States.

1.  If your organization uses sales tax jurisdictions for the calculation and reporting of sales taxes, the **Sales tax jurisdictions** configuration key must be selected.
    
    1.  Click Click **System administration** \> **Setup** \> **Licensing** \> **License configuration**.
    
    2.  In the left pane, expand the **General ledger** node, and then expand the **Sales tax** node.
    
    3.  Select **Sales tax jurisdictions**.

2.  If your organization is located in the United States, open the **General ledger parameters** form. (Click **General ledger** \> **Setup** \> **General ledger parameters**.) Click **Sales tax**, and then select the **Apply U.S. taxation rules** check box.
    
    For more information, see [(USA) Applying U.S. sales tax and use tax rules](usa-applying-u-s-sales-tax-and-use-tax-rules.md) and [General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\)).

3.  Complete the following sales tax setup activities:
    
      - Create a main account. For information, see [Create a main account](create-a-main-account.md).
    
      - Set up ledger posting groups for sales tax. For information, see [Set up ledger posting groups for sales tax](set-up-ledger-posting-groups-for-sales-tax.md).
    
      - Set up sales tax authorities. For information, see [Set up sales tax authorities](set-up-sales-tax-authorities.md).
    
      - Set up a sales tax authority as a vendor. For information, see [Set up a sales tax authority as a vendor](set-up-a-sales-tax-authority-as-a-vendor.md).
    
      - Set up a sales tax settlement period. For information, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).
    
      - Set up and use sales tax codes. For information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).
    
      - Set up sales tax jurisdictions, if your organization plans to use them. For information, see [Set up sales tax jurisdictions](set-up-sales-tax-jurisdictions.md).

4.  After the sales tax jurisdictions are set up, you must use the **Sales tax groups** form to attach the sales tax jurisdictions to sales tax groups. For information, see [Set up sales tax groups for jurisdictions](set-up-sales-tax-groups-for-jurisdictions.md).

  


