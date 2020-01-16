---
title: About graphics in product models
TOCTitle: About graphics in product models
ms:assetid: 1ec61a1c-5a80-40c9-b073-4e97779c542e
ms:mtpsurl: https://technet.microsoft.com/library/Aa496779(v=AX.60)
ms:contentKeyID: 36931866
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About graphics in product models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

With the help of graphics, you can present a drawing of the configured item that reflects the choices made in the user dialog box. If the user makes the setup for the drawings for a product model, the drawing will show on a separate tab in the user dialog box and it will be available for printing from the order line that the item is being configured from.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Graphics are set up in the **Graphic parameters** form. To open this form, click **Setup** \> **Graphic parameters** on the **Product model details** form.

When you set up graphics, the user can select which variables from the product model are reflected in the drawing. Files that have drawings that represent each combination of the values of the selected variable must be created and saved in one folder. Specify the path of this folder in the **Graphic parameters** form. When the user makes choices in the user dialog box, the drawing that reflects these choices is taken from the folder and the drawing shows on the **Graphic** tab. The graphic is updated every time that the user changes a value in the user dialog box. The correct drawing is selected from the specified folder by using the file name that is generated from the values of the variables reflected in the drawing.

File name generation is set up in the **Graphic parameters** form. In the **Format file name** field, the user should type the same amount of ‘%n’ signs as the amount of variables that have been selected in the **Variable** field.


> [!NOTE]
> <P>When you create drawings that represent all combinations of variables, name the created files to correspond with the file names that will be generated. You can shorten the names of some variable values. The number of characters representing each variable value is defined in the <STRONG>Length</STRONG> field.</P>



If the file is not found or if the user does not make any choices in the user dialog box, the default graphic is shown.


> [!NOTE]
> <P>A file with a default drawing must be also created beforehand.</P>



When the user accepts the configuration, a copy of the final drawing is copied to document handling in Microsoft Dynamics AX 2012 and connected to the configured line. The type of file in which the final drawing is saved is selected in the **Generate graphic documents of type** field in the **Product builder parameters** form.

If several variable values are used for one picture, you can use intervals to avoid creating a graphic for each value. You can set up the intervals for each variable in the **Interval** form, which opens when you click **Interval** in the **Graphic parameters** form.

## Example

When configuring a table lamp, the user can select any shade diameter from 20 to 50 centimeters. When you set up graphics for this lamp, create one file to be shown if the user selects the diameter from 20 to 35 and another one to be shown if it is from 35 to 50.

0 \< x \< 35 =\> 35

35 \< x \< 50 =\> 50

Therefore, if x is between 20 and 35, the value 35 will be used for graphics file name generation.

## See also

[About product models](about-product-models.md)

  


