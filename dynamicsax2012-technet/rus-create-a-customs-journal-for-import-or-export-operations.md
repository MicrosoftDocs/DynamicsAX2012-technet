---
title: (RUS) Create a customs journal for import or export operations
TOCTitle: (RUS) Create a customs journal for import or export operations
ms:assetid: 4e051c03-6306-4d1b-b027-01d6e40ac17e
ms:mtpsurl: https://technet.microsoft.com/library/JJ911377(v=AX.60)
ms:contentKeyID: 52075381
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Create a customs journal for import or export operations
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a customs journal for import or export operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Customs journal** form to create a customs journal for import or export operations. All procedures that are related to customs clearance are registered by using a customs journal.

1.  Click **Inventory management** \> **Common** \> **All customs journals**. Click **Customs journal**.
    

    > [!NOTE]
    > <P>You cannot create a customs journal for a non-inventoried or a category-based item.</P>



2.  In the **Log type** field, select **Import** to specify that the customs journal is for import operations.
    

    > [!NOTE]
    > <P>You can use a similar process to create a customs journal for export operations. You must select <STRONG>Export</STRONG> in the <STRONG>Log type</STRONG> field. You must also select a posting type for the customs journal in the <STRONG>Posting type</STRONG> field.</P>



3.  In the **Partner code** field, select the identification code of the foreign counteragent.

4.  In the **Agreement ID** field, select the contract registration number for the partner or vendor.

5.  In the **Customs code** field, select the code of a customs authority or office. The customs office code is set up in the **Customs counteragents** form.

6.  In the **CMR\\BOL** field, enter the Convention on the Contract for the International Carriage of Goods by Road (CMR) or bill of lading (BOL) number.

7.  In the **CMR\\BOL date** field, select the date of the CMR or BOL document.

8.  In the **TIR** field, enter the Transports Internationaux Routiers (TIR) number that is specified by the customs authorities. TIR monitors the movement of goods across international borders.

9.  In the **Declaration date** field, select the date when the customs declaration is created.

10. In the **Broker code** field, select the identification code of the customs broker.

11. In the **Requisites of customs services vendor** field group, in the **Agreement ID** field, select the contract registration number for the customs authority or customs broker.

12. In the **Customs clearance method** field, select the method that is used to calculate customs payment.

13. In the **Country/region** field, specify the default country or region that is associated with the foreign partner.

14. Select the **Include to the cost price** check box to include the customs fees with the cost price.

15. Click **OK** to create a customs journal.


> [!NOTE]
> <P>After you create a customs journal for import operations, you can calculate the storage fee and escort fee for goods and duty by using the <STRONG>Customs duty calculation</STRONG> form. The calculation results are updated in the <STRONG>Fees of storage and escort</STRONG> form. You can also verify the totals for the customs journal lines in the <STRONG>Totals</STRONG> form.</P>



## See also

[(RUS) Issue and post a customs cargo declaration for import or export operations](rus-issue-and-post-a-customs-cargo-declaration-for-import-or-export-operations.md)

[(RUS) Create customs journal (form)](https://technet.microsoft.com/library/jj853226\(v=ax.60\))

  


