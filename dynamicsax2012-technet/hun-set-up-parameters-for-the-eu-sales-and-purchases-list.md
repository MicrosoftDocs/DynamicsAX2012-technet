---
title: (HUN) Set up parameters for the EU sales and purchases list
TOCTitle: (HUN) Set up parameters for the EU sales and purchases list
ms:assetid: f68c2715-130d-4dc5-844a-04ff2480924c
ms:mtpsurl: https://technet.microsoft.com/library/JJ733166(v=AX.60)
ms:contentKeyID: 49685134
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up parameters for the EU sales and purchases list 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up parameters in Microsoft Dynamics AX that enable you to generate an EU sales list that reports sales that have been made to VAT-registered entities in other European Union (EU) member states. In some cases, you can generate an EU sales list that reports purchases made from these entities.


> [!NOTE]
> <P>For more information about how to create and submit the EU sales list, see <A href="generate-the-eu-sales-list.md">Generate the EU sales list</A>.</P>



Use the procedures below to set up parameters for the EU sales and purchase lists.

### Activate the VAT registration date as the reporting date

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the left pane, click **Sales tax**.

3.  On the **Tax options** FastTab, in the **Special report** field group, select the **Date of VAT register** check box.

### Configure the sales tax reporting type for the EU sales list

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Select or create the item sales tax group that you want to use with the EU sales list.

3.  In the **Reporting type** field, select **Item** or **Service**.

### Configure foreign trade parameters for the EU sales list

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  In the left pane, click **EU sales list**, and then select whether to report cash discounts in the EU sales list and whether to transfer purchases to the EU sales list.

3.  Select the report layout, and then click **Load XSLT files** to import the XML style sheets to use to generate the EU sales list.

4.  Enter the rounding rule amount. For example, if you want to round amounts to the nearest whole number, enter **1.00**. If you want to round amounts to the nearest half, enter **.50**.

5.  Select the method to use for rounding amounts:
    
      - **Normal** – Round the amount to the nearest unit that is specified in the **Rounding rule** field.
    
      - **Downward** – Round the amount down to the nearest unit that is specified in the **Rounding rule** field.
    
      - **Rounding-up** – Round the amount up to the nearest unit that is specified in the **Rounding rule** field.

6.  Select the **Use minimum value** check box to round amounts smaller than the rounding rule up to the rounding rule amount.

7.  In the left pane, click **Company information**.

8.  In the **Legal entity** field, select the legal entity that is used for EU sales list reporting.

9.  In the **Legal entity address** field, select the address that is used for EU sales list reporting.

10. In the **Building number** field, enter the building number for the legal entity’s address.

11. In the **Stairway number** field, enter the stairway number for the legal entity’s address.

12. In the **Floor number** field, enter the floor number for the legal entity’s address.

13. In the **Door number** field, enter the door number for the legal entity’s address.

## See also

[(HUN) EU sales list (modified form)](https://technet.microsoft.com/library/jj664282\(v=ax.60\))

  


