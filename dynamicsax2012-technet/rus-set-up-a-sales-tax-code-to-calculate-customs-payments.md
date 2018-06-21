---
title: (RUS) Set up a sales tax code to calculate customs payments
TOCTitle: (RUS) Set up a sales tax code to calculate customs payments
ms:assetid: 169134ff-75e8-4d0e-a5ac-65f78b72316b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733183(v=AX.60)
ms:contentKeyID: 49685151
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a sales tax code to calculate customs payments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Sales tax codes** form to set up a sales tax code that can be used to calculate customs payments. You can also specify a customs duty amount based on the volume or quantity of items.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Create a new sales tax code, or select an existing sales tax code.

3.  In the **Type of tax** field, select **Customs duty** or **Customs fee**.

4.  In the **Fee type** field, select the type of customs fee.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Customs fee</STRONG> in the <STRONG>Type of tax</STRONG> field.</P>



5.  In the **Quantity** field, enter the quantity of items that the customs fee is specified for.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Customs fee</STRONG> in the <STRONG>Type of tax</STRONG> field, <STRONG>Escort</STRONG> in the <STRONG>Fee type</STRONG> field, and <STRONG>Amount per unit</STRONG> in the <STRONG>Origin</STRONG> field, and if you select a unit of calculation in the <STRONG>Unit</STRONG> field.</P>



6.  In the **Complex rate** field, select the complex rate value that is applied to the customs duty.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Customs duty</STRONG> in the <STRONG>Type of tax</STRONG> field. If this field is blank, the complex rate value is an ad valorem duty. The ad valorem duty is based on the customs value of the items.</P>



7.  In the **Method of duty calculation** field, select the method that is used to calculate the customs duty.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Customs duty</STRONG> in the <STRONG>Type of tax</STRONG> field.</P>



8.  On the **Calculation** FastTab, in the **Unit** field, select the type of unit that is used to specify the quantity of items.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Customs duty</STRONG> in the <STRONG>Type of tax</STRONG> field.</P>



9.  Click **Values**.

10. In the **Values** form, on the **General** tab, in the **Amount rate** field, enter the amount for a specific rate of customs duty that is defined by the customs authorities.

11. In the **Currency** field, select the currency that is used for the calculation of customs duty.

12. In the **Calculated quantity** field, enter the quantity of items for the customs duty rate.

## See also

[(RUS) Assign a TN VED code to a customs payment](rus-assign-a-tn-ved-code-to-a-customs-payment.md)

[(RUS) Values of sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj678610\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

