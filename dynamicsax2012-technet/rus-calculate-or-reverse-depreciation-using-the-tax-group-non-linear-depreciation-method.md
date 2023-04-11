---
title: (RUS) Calculate or reverse depreciation using the tax group non-linear depreciation method
TOCTitle: (RUS) Calculate or reverse depreciation using the tax group non-linear depreciation method
ms:assetid: 97d2003e-8b7f-4e3d-a49a-dda918ef3202
ms:mtpsurl: https://technet.microsoft.com/library/JJ863540(v=AX.60)
ms:contentKeyID: 50395341
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate or reverse depreciation using the tax group non-linear depreciation method 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate depreciation in tax accounting by using the linear method or the non-linear method. You can also calculate tax depreciation by using the tax non-linear group depreciation method. This method allows you to specify a depreciation rate for each group, or a depreciation factor for each subgroup, to calculate the depreciation amount that is accrued for each depreciation group or subgroup.

You can group the depreciation register lines by depreciation group or subgroup by using the **FA depreciation (nonlinear method)**, **IA depreciation (nonlinear method)**, **FA - information about object**, and **IA - object information** tax registers. For more information, see [(RUS) Calculate the fixed assets depreciation (nonlinear method) register](rus-calculate-the-fixed-assets-depreciation-nonlinear-method-register.md) and [(RUS) Calculate the fixed asset depreciation register](rus-calculate-the-fixed-asset-depreciation-register.md).

Use the following procedures to set up a method of depreciation, and to calculate or reverse depreciation by using the tax group non-linear depreciation method.

## Set up the method of depreciation

You can create a tax non-linear group depreciation method in the **Depreciation methods** form. For more information, see [(RUS) Set up depreciation methods](rus-set-up-depreciation-methods.md) and [Depreciation methods and conventions](depreciation-methods-and-conventions.md).

1.  Click **Fixed assets (Russia)** \> **Setup** \> **Depreciation groups**.

2.  In the **Value model** field, select the value model that the depreciation group is defined for.
    

    > [!NOTE]
    > <P>You must specify the posting layer as <STRONG>Tax</STRONG> for the selected value model in the <STRONG>Value models</STRONG> form.</P>



3.  Create a new depreciation group. For more information, see [(RUS) Set up depreciation groups](rus-set-up-depreciation-groups.md).

4.  In the **Depreciation group** and **Name** fields, enter the depreciation group and name.

5.  In the **Depreciation method** field, select the **Tax nonlinear** method of depreciation.

6.  In the **Lifetime** field, enter the maximum asset service life, during which depreciation accrues for the fixed assets in the depreciation group. The value is expressed in months.

7.  In the **Year rate** field, enter the depreciation rate for the year.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Tax nonlinear group method</STRONG> as the method of depreciation.</P>



8.  On the **Subgroups** FastTab, in the **Depreciation subgroup** field, enter the identification code of the depreciation subgroup.
    

    > [!NOTE]
    > <P>This FastTab is available only if you select <STRONG>Tax nonlinear group method</STRONG> as the method of depreciation.</P>



9.  In the **Name** field, enter the name of the depreciation subgroup.

10. In the **Factor** field, enter the depreciation calculation ratio.

## Calculate fixed asset depreciation for fixed assets by using the tax non-linear group method

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  Create a new journal.

3.  In the **Name** field, select a journal name.

4.  In the **Description** field, modify the description of the journal.

5.  Click **Lines** to open the **Journal voucher** form.

6.  Click **Group operations** \> **Depreciation by group** to open the **Depreciation by group** form.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Tax nonlinear group method</STRONG> as the depreciation method, you cannot calculate the depreciation for a tax value model by using the single or group depreciation function.</P>



7.  In the **Transaction date** field, select the date of the transaction.

8.  Click **Select** to open the **Inquiry** form, and then enter the selection criteria for the fixed assets.

9.  Click **OK**. Depreciation transactions are created in the journal.

10. Click **Validate** \> **Validate** to validate the journal.

11. Click **Post** \> **Post** to post the journal. Corresponding fixed asset and ledger transactions are created.

## Reverse fixed asset depreciation

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  Create a new journal.

3.  In the **Name** field, select a journal name.

4.  In the **Description** field, modify the description of the journal.

5.  Click **Lines** to open the **Journal voucher** form.

6.  Click **Group operations** \> **Storno of depreciation** to open the **Storno of depreciation** form.

7.  In the **Date of storno** field, select a date for the depreciation reversal.

8.  In the **Accounting** field, select a fixed asset value model.

9.  Click **OK**. Depreciation reversal transactions are created in the journal.

10. Click **Validate** \> **Validate** to validate the journal.

11. Click **Post** \> **Post** to post the journal. The fixed asset depreciation transaction is reversed, and the ledger transaction is updated.

## Calculating depreciation bonus

The depreciation bonus is an additional depreciation amount that is assessed during the first year for some operational asset types. You must set up a posting profile and create an acquisition journal before you calculate the fixed asset depreciation bonus.

Use the **Depreciation bonus** form to calculate the depreciation bonus for fixed assets by using the **Tax nonlinear group method** as the depreciation method. When you create the depreciation transactions, a depreciated bonus is calculated for every asset. The bonus amount is calculated first, and then the depreciation from the cost is calculated, excluding the bonus. The bonus amount is not included in the total balance of the depreciation group.

## See also

[(RUS) Depreciation groups (form)](https://technet.microsoft.com/library/jj678328\(v=ax.60\))

[(RUS) Depreciation bonus (form)](https://technet.microsoft.com/library/jj853230\(v=ax.60\))

  


