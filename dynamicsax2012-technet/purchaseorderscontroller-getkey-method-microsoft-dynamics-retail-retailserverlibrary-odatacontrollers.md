---
title: PurchaseOrdersController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.purchaseorderscontroller.getkey(v=AX.60)
ms:contentKeyID: 62202164
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method

Gets the key for purchase order.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As PurchaseOrder _
) As String
'Usage
Dim entity As PurchaseOrder
Dim returnValue As String

returnValue = Me.GetKey(entity)
```

``` csharp
protected override string GetKey(
    PurchaseOrder entity
)
```

``` c++
protected:
virtual String^ GetKey(
    PurchaseOrder^ entity
) override
```

#### Parameters

  - entity  
    Type: PurchaseOrder  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PurchaseOrdersController Class](purchaseorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

