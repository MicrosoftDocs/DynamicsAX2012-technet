---
title: (RUS) Create a TN VED code and relate it to indicative prices for customs
TOCTitle: (RUS) Create a TN VED code and relate it to indicative prices for customs
ms:assetid: 994f5b96-865c-4be8-825c-7e7cd4228c88
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678520(v=AX.60)
ms:contentKeyID: 49387749
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- TN VED code
- customs duty
- indicative prices
- TNVED code
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a TN VED code and relate it to indicative prices for customs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **TN VED codes** form to create a Commodities Classification Code of the Foreign Economic Activity (TN VED) code that is used to calculate customs payments. After creating a TN VED code, you can set up the indicative, or estimated, prices defined by the customs authorities to import or export items in the **Indicative prices of TN VED** form.

1.  Click **Inventory management** \> **Setup** \> **Custom payments** \> **TN VED codes**.

2.  Create a TN VED code.

3.  In the **TN VED code** field, enter the 10-character TN VED identification code. TN VED codes are defined in Russian customs legislation documents.

4.  In the **Name** field, enter the name of the TN VED code.
    

    > [!NOTE]
    > <P>To block a TN VED code, select the <STRONG>Blocked</STRONG> check box.</P>



5.  In the **Description** field, enter a brief description of the TN VED code.

6.  Click **Setup** \> **Indicative prices**.

7.  Create a new line.

8.  In the **From date** field, select the activation date of the indicative price for the import or export of items.

9.  In the **Customs code** field, select the customs counteragent code that the indicative prices are selected for.

10. In the **TN VED code** field, enter the TN VED code that the indicative prices are selected for.

11. In the **Price for import** and **Price for export** fields, enter the indicative prices for import and export.

12. In the **Currency** field, select the currency code for the indicative price.

13. In the **Quantity** field, enter the quantity of items for the indicative price.

14. In the **Unit** field, select the type of unit for the indicative price.

## See also

[(RUS) Assign a TN VED code to a customs payment](rus-assign-a-tn-ved-code-to-a-customs-payment.md)

[(RUS) TN VED codes (form)](https://technet.microsoft.com/en-us/library/jj711428\(v=ax.60\))

[(RUS) Indicative prices of TN VED (form)](https://technet.microsoft.com/en-us/library/jj711361\(v=ax.60\))

  


