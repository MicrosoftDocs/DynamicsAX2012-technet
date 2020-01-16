---
title: About BOM calculations
TOCTitle: About BOM calculations
ms:assetid: 7c625da9-ecdb-47c1-ae90-9b03091601f6
ms:mtpsurl: https://technet.microsoft.com/library/Aa571515(v=AX.60)
ms:contentKeyID: 36058264
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About BOM calculations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Calculation** form is used to calculate a manufactured item’s cost and to generate an associated item cost record within a costing version. The **Calculation** form can also be used to calculate a manufactured item’s sales price and to generate an associated item sales price record within a costing version. The cost roll-up and sales price calculations are termed BOM calculations, or bill of material (BOM) calculations, because you initiate them from the **Calculation** form.

Usage of the **Calculation** form varies slightly based on how you initiate the BOM calculations. Usage also depends on whether the BOM calculations involve a costing version for standard costs or planned costs, and depends on several policies defined within the costing version that is being used in the BOM calculations.


> [!NOTE]
> <P>A variation of the <STRONG>Calculation</STRONG> form is used in the context of a sales order, sales quotation, or service order line item. These are termed order-specific BOM calculations. An order-specific BOM calculation generates a calculation record that is displayed on the <STRONG>BOM calculation results</STRONG> form (rather than an item cost record within a costing version). The calculation record includes a calculated cost and a calculated sales price.</P>



The **Calculation** form can be initiated for a single manufactured item or for a costing version.

Initiate BOM calculations from the **Item price** form in order to calculate costs for a single manufactured item. The **Calculation** form inherits the item identifier, and the **Calculation** form requires specification of the costing version, BOM version, route version, calculation quantity, calculation date, and site.

  - The BOM version and route version will initially display the active versions for the item, site, date, and calculation quantity, but the default can be overridden with approved versions.

  - The calculation quantity will initially display the item’s standard order quantity, but the default can be overridden.

  - The calculation date or site can be mandated by the costing version, or allow user-specified values when the date or site are not mandated in the costing version. A future calculation date determines the use of pending cost records. BOM calculations will use a pending cost record with the nearest from-date on or before the calculation date.

Initiate BOM calculations from the **Costing version setup** form (or the **Costing version maintenance** form) in order to calculate costs for all manufactured items or for selected items, or for updating items on a where-used basis. The **Calculation** form inherits the costing version.

  - The calculations assume the use of the active BOM version and route version for a manufactured item (and the related site, date, and quantity), unless a manufactured component has a specified sub-BOM or subroute.

  - The calculations assume the use of the standard order quantity for manufactured items, which provides the basis for calculating component quantities, for determining the relevant BOM versions and route versions (when you use quantity-sensitive BOMs and routes), and for amortizing constant costs. The assumption does not apply when a manufactured component has a BOM line type of production or vendor, or when you use a make-to-order explosion mode for the BOM calculations, because quantities will reflect the specified calculation quantity.

  - The calculation date or site can be mandated by the costing version, or the calculation date or site can allow user-specified values when not mandated by the costing version.

Other variations in BOM calculations reflect the costing type and restrictions of the costing version, as summarized in the following diagram and described in the text that follows.

BOM calculations with standard costs must be restricted by costing version policies because the restrictions ensure standard costing principles. Standard costing principles require the enforcement of restrictions about the use of standard costs for purchased items, a single level explosion mode, and the inclusion of miscellaneous charges in unit costs. In contrast, BOM calculations with planned costs do not have to follow standard costing principles. These BOM calculations can use different explosion modes, alternative sources of cost data for purchased items, and optional enforcement of restrictions within the costing version.

BOM calculations with standard costs. Policies within the costing version (for standard costs) can mandate enforcement of five BOM calculation policies. The recording restriction check box within the costing version mandates one of these policies, where miscellaneous charges must be included in the unit price. Miscellaneous charges for purchased items can be manually entered, whereas the miscellaneous charges for manufactured items reflect the calculated amortization of constant costs.

The calculation restriction check box within the costing version mandates the other four BOM calculation policies.

  - The source of purchased items’ cost contributions must be based standard costs. That is, BOM calculations must use the item cost records within the specified costing version, or within the fallback that contains standard costs.

  - The explosion mode must be single level, which ensures accurate and consistent calculation of standard costs.

  - The profit setting must be mandated in order to obtain consistent results in calculating the items’ sales price. The costing version must allow content of sales prices in order to use the profit setting and to generate the item sales price records.

  - The fallback principle must be mandated, where the principle can be none, active cost records, or a specified costing version.

BOM calculations with planned costs. Policies within the costing version (for planned costs) can optionally mandate enforcement of five BOM calculation policies, or simply provide default values. The recording restriction check box within the costing version determines whether the BOM calculation policy about miscellaneous charges will be mandated, or act as a default value. Miscellaneous charges can be optionally included in the unit price.

The calculation restriction check box within the costing version determines whether the other four BOM calculation policies will be mandated or act as default values.

  - The source of a purchased item’s cost contributions can be the item cost records within a costing version or the source can be defined by the BOM calculation group that is assigned to the item. For example, the BOM calculation group could define purchase price trade agreements as the source of cost contribution data.

  - The explosion mode can be single level, multilevel, make-to-order, or based on the BOM line item. The explosion mode for BOM line type replicates the cost calculation logic for production order estimates.

  - The profit setting can be mandated or a default value. The costing version must allow content of sales prices in order to use the profit setting and to generate the item sales price records.

  - The fallback principle can be mandated or a default value, where the principle can be none, active cost records, or a specified costing version.

BOM calculations generate an Infolog that contains warning messages and other types of messages. Several BOM calculation policies determine the types of messages in the Infolog. The applicable warning conditions are defined within the BOM calculation group that is assigned to items, but you can override these warning conditions when you initiate a BOM calculation. When using the fallback principle, it is often helpful to display the fallback information as messages in the Infolog. When trying to update calculated costs for items with missing cost records, it is also helpful to identify items that did not get updated as messages in the Infolog.

## See also

[About costing versions](about-costing-versions.md)

[About costing versions for standard costs](about-costing-versions-for-standard-costs.md)

[About information used in BOM calculations with standard costs](about-information-used-in-bom-calculations-with-standard-costs.md)

[About amortizing constant costs for a manufactured item](about-amortizing-constant-costs-for-a-manufactured-item.md)

[About displaying charges for a manufactured item](about-displaying-charges-for-a-manufactured-item.md)

[About manufactured items that are treated as purchased items](about-manufactured-items-that-are-treated-as-purchased-items.md)

[About BOM calculations that use the fallback principle](about-bom-calculations-that-use-the-fallback-principle.md)

[About BOM calculation of a suggested sales price](about-bom-calculation-of-a-suggested-sales-price.md)

  


