---
title: (HUN) About indirect trade
TOCTitle: (HUN) About indirect trade
ms:assetid: 2ba9601b-8a73-4346-bbee-b77b17f12d10
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ874423(v=AX.60)
ms:contentKeyID: 50619740
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EU
- Intrastat
- Hungary indirect trade
- indirect trade
---

# (HUN) About indirect trade [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An indirect trade transaction occurs when your organization purchases items from or sells items to a country/region outside the European Union (EU), and the items cross another EU states’ borders during shipment. These transactions must be recorded for Intrastat reporting.

In Microsoft Dynamics AX, these transactions are recorded in the **Intrastat** form, which is used to complete Intrastat reporting.

## Imported items

If your organization imports items from a country/region outside the EU, and the items cross the borders of another EU member state, an indirect trade transaction occurs. This transaction must be included in the Intrastat reports that your organization generates.

For example, Contoso Corporation in Hungary purchases 100 speaker frames from Fabrikam USA. This purchase is not considered an indirect trade transaction. However, Fabrikam USA sends the speaker frames by air to Germany and then the speaker frames are put on a train to Hungary. The transaction is now an indirect trade transaction because the speaker frames crossed German boarders. Contoso must include the transaction on the **Intrastat** report.

A customs duty must also be paid for items that are imported into an EU member state from a country/region that is outside the EU if the intent is to release the items in other EU member states for free circulation.

Customs duty on imported items is recorded in one of the following ways:

  - The items are transported through the other member states as a simple transit. When the items are released into free circulation, the customs procedure is performed in Hungary.

  - The items are released into free circulation in another member state on behalf of the importing organization in Hungary. The importing organization’s community tax registration number is used to record customs duty. The items are then transferred to Hungary.

## Exported items

If your organization exports items to a country/region outside the EU, and the items cross the borders of another EU member state, an indirect trade transaction occurs and must be included on the **Intrastat** report.

For example, the Fabrikam headquarters in China purchases 50 LCD monitors from the Contoso Corporation in Hungary. This purchase is not considered an indirect trade transaction. However, Contoso ships the monitors by train to Austria, where the monitors are put on a plane to China. Because the monitors traveled through Austria, the transaction is now an indirect trade transaction and must be included on Contoso’s Intrastat report.

A customs export procedure must be completed for items that are imported to an EU member state from a country/region that is outside the EU if the intent is to release the items in other EU member states for free circulation.

Customs duty on exported items is recorded in one of the following ways:

  - The export customs procedure is performed in Hungary and the items are transferred through the other member states as simple transit. This does not have to be included on the Intrastat report.

  - Items are in free circulation when they are transferred to the other member state from Hungary. The export customs procedure is completed in the member state where the items are located on behalf of the exporting organization in Hungary. The exporting organization’s community tax registration number is used to record customs duty. This is called indirect export, which must be recorded in the **Intrastat** forms as a dispatch to the other member state. If the final destination for the exported items is outside the EU, the country/region code of the final destination must be included on the Intrastat report.

## See also

[About Intrastat](about-intrastat.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

