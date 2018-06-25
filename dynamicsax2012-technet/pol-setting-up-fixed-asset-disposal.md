---
title: (POL) Setting up fixed asset disposal
TOCTitle: (POL) Setting up fixed asset disposal
ms:assetid: ac02a300-5f49-4357-b96d-e558f7160478
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ730412(v=AX.60)
ms:contentKeyID: 49636331
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Setting up fixed asset disposal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up the features that organizations in Poland can use to dispose of fixed assets. The features for fixed asset disposal in Poland differ from the standard features as follows:

  - You can specify the individual assets to dispose of when you use the sales disposal method.

  - You can partially dispose of fixed assets.

  - You can dispose of fixed assets by using a template that contains the accounts to use for the disposal.

This topic does not describe the standard features for fixed asset disposal. For information about those features, see [About fixed asset disposal](about-fixed-asset-disposal.md).

## Disposal of specific fixed assets

You can control the sales method of fixed asset disposal by enabling a validation that requires that individual assets be specified as eligible for sale. You enable the validation by specifying the following:

  - To require that fixed assets be specified as eligible for sale, select the **Check whether asset can be sold** check box in the **Fixed assets** area of the **Fixed assets parameters** form.

  - Define the default sales account to use when you dispose of an asset. To do this, select the account in the **Sales account** field in the **Fixed assets** area of the **Fixed assets parameters** form. By default, the account is used on the free text invoice for lines that contain an asset that can be sold. When you create a sales disposal transaction by using the fixed asset journal, the sales account for the related posting profile is used.

  - Select the **Permission to sell fixed asset** check box on the **Reference and notes** FastTab in the **Fixed assets** form for each asset. The assets become available on free text invoice lines and in fixed asset journals when the sales disposal method is used.

## Partial disposal of fixed assets

The standard features for fixed asset disposal allow for the disposal of only a whole fixed asset. In Poland, you can partially dispose of a fixed asset. Partial disposal is useful, for example, when a conference table and chairs are bought as a set and are handled as one asset. To replace only the chairs, you must be able to dispose of the old chairs without disposing of the other component of the asset, the table, at the same time.

The requirements for partially disposing of a fixed asset are as follows:

  - The fixed asset must be eligible for sale.

  - The percentage of the net book value of the fixed asset to dispose of is specified in the **Partial sales** field. When you dispose of an asset, the field is available in one of the following forms:
    
      - In Accounts receivable, in the **Free text invoice** form, click the **Line details** FastTab.
    
      - In Fixed assets, in the **Fixed assets** form, click **Lines**, and then click the **General** tab.

You can partially dispose of a fixed asset by selecting the asset, and then entering the percentage of the net book value to dispose of in the **Partial sales** field. The value can be from 0 to 100. The default percentage is 100. When you select the asset, the **Amount** field on the journal line displays the net book value. When you enter a percentage in the **Partial sales** field, the value in the **Amount** field is recalculated. The same is true in reverse. You can always change the percentage on free text invoices. However, you can change it in fixed asset journals only when you dispose of a fixed asset by using the sales disposal method.

You can create and post any number of disposal transactions, up to 100 percent of the net book value. A transaction that has a partial sales percentage of 100 is final, and the status of the fixed asset changes from **Open** to **Sold** or **Scrapped**.

## Fixed asset disposal by using templates

When you are ready to dispose of a fixed asset, you can use a template that lets you specify the disposal accounts:

  - **Value model** – The value model for which to set up or update the posting accounts for asset disposal.

  - **Main account** – The main account to use when you set up or update the accounts for posting the disposal of an asset.

  - **Offset account** – The offset account to use when you set up or update the accounts for posting the disposal of an asset.

You can also select the **Overwrite?** check box to use the template to overwrite the accounts that were previously selected.

The following path describes how to open the template: Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**. Click **Disposal**, and then select either **Sale** or **Scrap**. In the **Disposal parameters** form, click **Create template**.

## See also

[(POL) Fixed asset details (modified form)](https://technet.microsoft.com/en-us/library/jj730411\(v=ax.60\))

[(POL) Fixed assets parameters (modified form)](https://technet.microsoft.com/en-us/library/jj730406\(v=ax.60\))

[(POL) Disposal parameters (modified form)](https://technet.microsoft.com/en-us/library/jj730407\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

