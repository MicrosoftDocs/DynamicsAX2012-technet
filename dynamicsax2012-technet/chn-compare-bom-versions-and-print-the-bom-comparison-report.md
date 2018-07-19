---
title: (CHN) Compare BOM versions and print the BOM comparison report
TOCTitle: (CHN) Compare BOM versions and print the BOM comparison report
ms:assetid: 5ee58cb2-e8e7-40f8-abe7-48ce4f63eb43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664050(v=AX.60)
ms:contentKeyID: 49384633
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BOM version
- BOM comparison
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Compare BOM versions and print the BOM comparison report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A **BOM comparison** report compares BOM versions for a product or compares differences in components among a group of similar products. The **BOM comparison** report helps you to optimize the inventory and sales management process by providing information about a product and its versions.

You can run automatic BOM comparisons from the **BOM comparison** form. You can compare up to five BOM versions. You can also select the inventory dimensions to display on the report.

1.  Click **Inventory management** \> **Inquiries** \> **BOM comparison**.

2.  In the **Product** field, in the **BOM version 1** field group, select the product for which the BOM versions are to be compared. You can also select the products to be compared in the subsequent BOM version field groups.

3.  In the **BOM version** field, in the **BOM version 1** field group, select the BOM version for the product to be compared. You can also select field values in the subsequent BOM version field groups. You can select only one BOM identification code for a BOM version.

4.  In the **Compare field** field, select **BOM quantity**.

5.  In the **Cost type** field, select from the following options:
    
      - **Inventory cost** – The inventory unit cost is displayed as the comparison cost.
    
      - **Purchase price** – The most recent purchase price is displayed as the comparison cost.

6.  Click **Refresh** to generate the BOM comparison details, which are displayed on the **Overview** tab. Line details for each product are shown on tabs that are adjacent to the **Overview** tab.

7.  Click **Inventory** \> **Dimensions display** to open the **Dimensions display** form, and then select the inventory dimensions to be displayed in the comparison report.
    

    > [!NOTE]
    > <P>This button is available only for the individual BOM version tabs. Fields related to inventory dimensions are displayed, based on your selections in the <STRONG>Dimensions display</STRONG> form.</P>



8.  Click **Print** to open the **BOM comparison** report, and then click **OK** to generate and print the **BOM comparison** report.

9.  Close the form.

## See also

[Create a BOM and BOM version](create-a-bom-and-bom-version.md)

[(CHN) BOM comparison (form)](https://technet.microsoft.com/en-us/library/jj664075\(v=ax.60\))

[(CHN) About BOM comparison](chn-about-bom-comparison.md)

  


