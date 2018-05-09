---
title: SalesOrdersController.CreateEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CreateEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.CreateEntity(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.salesorderscontroller.createentity(v=AX.60)
ms:contentKeyID: 62203469
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.CreateEntity
dev_langs:
- CSharp
- C++
- VB
---

# CreateEntity Method

The create sales order entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function CreateEntity ( _
    entity As SalesOrder _
) As SalesOrder
'Usage
Dim entity As SalesOrder
Dim returnValue As SalesOrder

returnValue = Me.CreateEntity(entity)
```

``` csharp
protected override SalesOrder CreateEntity(
    SalesOrder entity
)
```

``` c++
protected:
virtual SalesOrder^ CreateEntity(
    SalesOrder^ entity
) override
```

#### Parameters

  - entity  
    Type: SalesOrder  

#### Return Value

Type: SalesOrder  
The SalesOrder.  

## See Also

#### Reference

[SalesOrdersController Class](salesorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

