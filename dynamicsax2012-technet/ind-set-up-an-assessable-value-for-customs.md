---
title: (IND) Set up an assessable value for customs
TOCTitle: (IND) Set up an assessable value for customs
ms:assetid: ce0376ea-77f6-4282-b1c5-6f8d96d59215
ms:mtpsurl: https://technet.microsoft.com/library/JJ664923(v=AX.60)
ms:contentKeyID: 49386252
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up an assessable value for customs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **Assessable value** form is available only for import orders. For an order other than an import order, landing charges are not included in the assessable value at the time of calculation. You can select the basis for the calculation of customs duty and view the consolidated miscellaneous charges value.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order and on the **Action Pane**, on the **Purchase order** tab, in the **Maintain** group, click **Edit**. On the **Purchase order** form, on the **Purchase order lines** tab, click **Purchase order line** \> **Assessable value**.

2.  View the purchase order number of import orders in the **Purchase order** field.

3.  View the net amount for the purchase order line in the **Net amount** field.

4.  Select the basis for the calculation of customs duty in the **Basis** field from the following options:
    
      - **FOB** — If the Free on Board (FOB) option is selected, the **Misc. charges** field is updated with the value set in the **Misc. charges transactions** form only if the **Assessable value** check box is selected in the **Misc. charges transaction** form.
    
      - **CIF** — If the Cost, insurance, and freight (CIF) option is selected, the **Misc. charges** field is not updated with the value set in the **Misc. charges transactions** form, even if the **Assessable value** check box is selected.

5.  View the sum of the net amount and the miscellaneous charges amount in the **CIF** field.

6.  View or modify the landing charges percentage in the **Landing charges pct**. field, and view the multiplication of landing charges percentage and the CIF amount in the **Landing charges** field.

7.  View the assessable value in the **Assessable value** field, that is, the addition of the CIF amount and the landing charges amount.
    

    > [!NOTE]
    > <P>All the amounts on the <STRONG>Overview</STRONG> tab are in the transaction currency.</P>



8.  Click the **General** tab to view the following the invoice currency, customs currency, and default currency details:
    
      - The FOB, Misc. charges, CIF, landing charges pct., landing charges, and assessable value in the invoice currency and customs currency.
    
      - The exchange rate in customs currency and default currency and the base amount in default currency.
    

    > [!NOTE]
    > <P>Information displayed under customs currency is based on the Customs exchange rate.</P>



9.  Click **Misc. charges** to open the **Misc. charges transactions** form.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\))

[(IND) Assessable value (form)](https://technet.microsoft.com/library/jj664952\(v=ax.60\))

  


