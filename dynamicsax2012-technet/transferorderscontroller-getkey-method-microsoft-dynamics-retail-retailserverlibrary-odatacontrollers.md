---
title: TransferOrdersController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.transferorderscontroller.getkey(v=AX.60)
ms:contentKeyID: 62202836
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method

Gets the key for a given transfer order.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As TransferOrder _
) As String
'Usage
Dim entity As TransferOrder
Dim returnValue As String

returnValue = Me.GetKey(entity)
```

``` csharp
protected override string GetKey(
    TransferOrder entity
)
```

``` c++
protected:
virtual String^ GetKey(
    TransferOrder^ entity
) override
```

#### Parameters

  - entity  
    Type: TransferOrder  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))key.  

## See Also

#### Reference

[TransferOrdersController Class](transferorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

