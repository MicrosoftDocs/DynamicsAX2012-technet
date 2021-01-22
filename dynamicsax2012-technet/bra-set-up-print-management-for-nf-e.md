---
title: (BRA) Set up print management for NF-e
TOCTitle: (BRA) Set up print management for NF-e
ms:assetid: e68ab728-85de-4753-b6bb-9ce06bb9361e
ms:mtpsurl: https://technet.microsoft.com/library/Dn126110(v=AX.60)
ms:contentKeyID: 52075282
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- print management
- BRA
- Brazil
- NF-e
- electronic fiscal document
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up print management for NF-e 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to set up the format that is used to print an electronic fiscal document (NF-e). To print the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) automatically after an NF-e is approved by the Secretaria da Fazenda (SEFAZ), you must set up all documents that generate an NF-e in print management.

## Set up print management for a customer NF-e

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.

2.  In the **Print management setup** form, in the left pane, expand the **Module - accounts receivable** node.

3.  Expand the **Documents** node, and then expand the **Customer invoice** node.

4.  Right-click **Original**, and then click **New**.

5.  Enter information in the following fields:
    
      - In the **Description** field, enter a brief description for the conditional setting, and then click **Select**.
    
      - In the lower pane, select a line, and then click **Remove**. Repeat this for all lines.
    
      - Click **Add**, and then in the **Table** field, select **Fiscal document header**.
        

        > [!NOTE]
        > <P>If <STRONG>Fiscal document header</STRONG> is not available in the <STRONG>Table</STRONG> field in the <STRONG>Print management setup</STRONG> form, right-click <STRONG>Customer invoice journal</STRONG> or <STRONG>Customer packing slips</STRONG> in the upper pane, and then click <STRONG>1:n</STRONG> &gt; <STRONG>Fiscal document header</STRONG>.</P>

    
      - In the **Field** field, select **Model**.
    
      - In the **Criteria** field, select 55, and then click **OK**.
    
      - In the **Print management setup** form, in the right pane, in the **Report format** field, select **EFDocDANFE\_BR.Report**.

6.  In the left pane, expand the **Free text invoice** node, right-click **Original**, and then click **New**.

7.  Repeat step 5 to set up a conditional setting and report format for free text invoices.

8.  In the left pane, expand the **Sales order packing slip** node, right-click **Original**, and then click **New**.

9.  Repeat step 5 to set up a conditional setting and report format for sales order packing slips.

## Set up print management for a vendor NF-e

1.  Click **Accounts payable** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.

2.  In the **Print management setup** form, in the left pane, expand the **Module - accounts payable** node.

3.  Expand the **Documents** node, and then expand the **Vendor invoice** node.

4.  Right-click **Original**, and then click **New**.

5.  Enter information in the following fields:
    
      - In the **Description** field, enter a brief description for the conditional setting, and then click **Select**.
    
      - In the lower pane, select a line, and then click **Remove**. Repeat this for all lines.
    
      - Click **Add**, and then in the **Table** field, select **Fiscal document header**.
        

        > [!NOTE]
        > <P>If <STRONG>Fiscal document header</STRONG> is not available in the <STRONG>Table</STRONG> field in the <STRONG>Print management setup</STRONG> form, right-click <STRONG>Vendor invoice journal</STRONG> in the upper pane, and then click <STRONG>1:n</STRONG> &gt; <STRONG>Fiscal document header</STRONG>.</P>

    
      - In the **Field** field, select **Model**.
    
      - In the **Criteria** field, select 55, and then click **OK**.
    
      - In the **Print management setup** form, in the right pane, in the **Report format** field, select **EFDocDANFE\_BR.Report**.

## Set up print management for a project NF-e

1.  Click **Project management and accounting** \> **Setup** \> **Forms** \> **Form setup**. Click **Print management**.

2.  In the **Print management setup** form, in the left pane, expand the **Module - project** node.

3.  Expand the **Documents** node, and then expand the **Project invoice with billing rules** node.

4.  Right-click **Original**, and then click **New**.

5.  Enter information in the following fields:
    
      - In the **Description** field, enter a brief description for the conditional setting, and then click **Select**.
    
      - In the lower pane, select a line, and then click **Remove**. Repeat this for all lines.
    
      - Click **Add**, and then in the **Table** field, select **Fiscal document header**.
        

        > [!NOTE]
        > <P>If <STRONG>Fiscal document header</STRONG> is not available in the <STRONG>Table</STRONG> field in the <STRONG>Print management setup</STRONG> form, right-click <STRONG>Project invoice</STRONG> in the upper pane, and then click <STRONG>1:n</STRONG> &gt; <STRONG>Fiscal document header</STRONG>.</P>

    
      - In the **Field** field, select **Model**.
    
      - In the **Criteria** field, select 55, and then click **OK**.
    
      - In the **Print management setup** form, in the right pane, in the **Report format** field, select **EFDocDANFE\_BR.Report**.

6.  In the **Print management setup** form, in the left pane, expand the **Project invoice without billing rules** node, right-click **Original**, and then click **New**.

7.  Repeat step 5 to set up a conditional setting and report format for project invoice without billing rules.

## Set up print management for a tax fiscal document NF-e

1.  Click **General ledger** \> **Setup** \> **Print management**.

2.  In the **Print management setup** form, in the left pane, expand the **Module - general ledger** node.

3.  Expand the **Documents** node, and then expand **Tax fiscal document** node.

4.  Right-click **Original**, and then click **New**.

5.  Enter information in the following fields:
    
      - In the **Description** field, enter a brief description for the conditional setting, and then click **Select**.
    
      - In the lower pane, select a line, and then click **Remove**. Repeat this for all lines.
    
      - Click **Add**, and then in the **Table** field, select **Fiscal document header**.
        

        > [!NOTE]
        > <P>If <STRONG>Fiscal document header</STRONG> is not available in the <STRONG>Table</STRONG> field in the <STRONG>Print management setup</STRONG> form, right-click <STRONG>Tax fiscal document</STRONG> in the upper pane, and then click <STRONG>1:n</STRONG> &gt; <STRONG>Fiscal document header</STRONG>.</P>

    
      - In the **Field** field, select **Model**.
    
      - In the **Criteria** field, select 55, and then click **OK**.
    
      - In the **Print management setup** form, in the right pane, in the **Report format** field, select **EFDocDANFE\_BR.Report**.

## Set up print management for a transfer order NF-e

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **Inventory and warehouse management parameters** form, click **Print management**.

3.  In the **Print management** area, click **Print management** to open the **Print management setup** form.

4.  In the left pane, expand the **Module - inventory management** node.

5.  Expand the **Documents** node, and then expand the **Fiscal document** node.

6.  Right-click **Original**, and then click **New**.

7.  Enter information in the following fields:
    
      - In the **Description** field, enter a brief description for the conditional setting, and then click **Select**.
    
      - In the lower pane, select a line, and then click **Remove**. Repeat this for all lines.
    
      - Click **Add**, and then in the **Table** field, select **Fiscal document header**.
    
      - In the **Field** field, select **Model**.
    
      - In the **Criteria** field, select 55, and then click **OK**.
    
      - In the **Print management setup** form, in the right pane, in the **Report format** field, select **EFDocDANFE\_BR.Report**.

You can also set up the **Fiscal establishment ID** field in the **Field** field in the **Fiscal document header** table as an additional criterion to set a specific destination to print the DANFE.

## See also

[Set up print management for a module](set-up-print-management-for-a-module.md)

[Set up print management for a customer or vendor](set-up-print-management-for-a-customer-or-vendor.md)

[Print management setup (form)](https://technet.microsoft.com/library/hh209383\(v=ax.60\))

  


