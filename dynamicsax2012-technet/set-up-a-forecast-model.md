---
title: Set up a forecast model
TOCTitle: Set up a forecast model
ms:assetid: b3aed959-6ce8-4f5a-b781-e4e6697d95d4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572021(v=AX.60)
ms:contentKeyID: 36059072
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- forecast model
- aggregate forecast
- create forecast model
- create forecast submodel
---

# Set up a forecast model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A forecast model names and identifies a specific forecast. You must create a forecast model before you can create the actual forecast lines.

You can set up a forecast model with two levels so that one model includes one or more other models, or submodels. This structure enables you to aggregate the individual forecasts. You must create a forecast model before you can assign it to be a submodel of another forecast model.

## Create a forecast model

1.  Click **Inventory management** \> **Setup** \> **Forecast** \> **Forecast models**.

2.  In the grid section, press CTRL+N or click **New** to create a forecast model.

3.  Enter an identifier and a name for the model.

4.  In the header section, you can define settings for the forecast.

## Assign a forecast model as a submodel

1.  In the grid section, select the forecast model for which you want to set up a submodel.

2.  On the **Submodel** FastTab, press CTRL+N or click **Add** to create a submodel.

3.  In the **Submodel** field, select the model that you want to designate as a submodel and then enter a name for it.

**Example**

To set up a forecast model structure where the top-level forecast model, named Total, consists of two submodels which are named East and West, follow this procedure:

1.  In the grid section, create three forecast models: Total, East, and West.

2.  Select the Total model line.

3.  On the **Submodel** FastTab, create a submodel line, and then select the East model.

4.  On the **Submodel** FastTab, create a submodel line, and then select the West model.

## See also

[Forecast models (form)](https://technet.microsoft.com/en-us/library/aa620573\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

