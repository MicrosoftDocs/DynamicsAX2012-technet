---
title: (RUS) Set up fixed asset groups
TOCTitle: (RUS) Set up fixed asset groups
ms:assetid: 43dd1581-6702-4964-9b88-92bf9e1d2edc
ms:mtpsurl: https://technet.microsoft.com/library/JJ923414(v=AX.60)
ms:contentKeyID: 52075373
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up fixed asset groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Fixed asset groups are defined to group fixed assets. By defining fixed asset groups, you accomplish the following goals:

  - Simplify the setup of fixed assets and posting profiles for fixed assets.

  - Simplify the creation of queries and reports.

  - Create a template, so that common information is copied by default into the records of new and similar fixed assets that are acquired by the company.

Use the **FA groups** form to define fixed asset groups for working clothes and special rigging accounting. To each group that you define, you assign an appropriate type that is specified in the **Type of group** field. You can also use the **FA group value models** form to set up value models for the defined fixed asset groups, and specify the duration of the wear or usage period of an asset.

1.  Click **Fixed assets (Russia)** \> **Setup** \> **FA groups**.

2.  Press CTRL+N to create a new fixed asset group.

3.  In the **FA group** field, enter the code for the fixed asset group. In the **Name** field, enter the name of the fixed asset group.

4.  In the **Type of group** field, select **Fixed assets**, **Working clothes**, **Special rigging**, or **NVFA** (not valuable fixed asset) as the type of fixed asset group.

5.  Select the **Autonumeration FA** check box to generate a fixed asset number automatically when you create fixed assets for the group in the **Fixed assets** form.

6.  In the **FA autonumbering sequence** field, select a number series for automatic number generation.

7.  In the **VAT refunding** field, select the start date for refunding value-added tax (VAT) for the fixed assets. Select one of the following options:
    
      - **Acquisition date** – Start refunding VAT from the acquisition date.
    
      - **Depreciation run date** – Start refunding VAT from the date of depreciation.

8.  Select the **Barcodes autonumeration** check box to generate bar codes automatically for the fixed assets in the group.

9.  In the **Barcode autonumeration sequence** field, select a number series for automatic bar code generation.

10. Click **Value models** to open the **FA group value models** form.

11. In the **Value model** field, select a value model for the fixed asset group.

12. In the **Depreciation group** field, select a depreciation group for the fixed asset group.
    

    > [!NOTE]
    > <P>When you create a fixed asset for a specific fixed asset group, the value model and depreciation group that you define in this form are displayed by default in the <STRONG>Value models</STRONG> form and cannot be changed.</P>



13. Select the **Service life by rate** check box to specify the wear or usage period for the asset, based on the lifetime that is specified during the issue process in the **Working clothes/Special rigging/NVFA issue journal** form. If you do not select this check box, the usage period is determined by the depreciation group.
    

    > [!NOTE]
    > <P>The <STRONG>Service life by rate</STRONG> check box is available only when you select <STRONG>Working clothes</STRONG>, <STRONG>Special rigging</STRONG>, or <STRONG>NVFA</STRONG> in the <STRONG>Type of group</STRONG> field in the <STRONG>FA groups</STRONG> form. If you select this check box, the lifetime that is specified in the <STRONG>Issue and usage rates</STRONG> form is updated in the <STRONG>Lifetime</STRONG> field in the <STRONG>Working clothes/Special riggings/NVFA issue journal lines</STRONG> form when you create an issue journal for the asset. The lifetime is updated on the working clothes or special rigging card.</P>



## See also

[(RUS) FA groups (form)](https://technet.microsoft.com/library/jj853159\(v=ax.60\))

[(RUS) FA group value models (form)](https://technet.microsoft.com/library/jj853199\(v=ax.60\))

  


