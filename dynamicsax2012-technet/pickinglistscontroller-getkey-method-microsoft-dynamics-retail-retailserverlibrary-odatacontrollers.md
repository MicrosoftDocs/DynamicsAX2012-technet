---
title: PickingListsController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.pickinglistscontroller.getkey(v=AX.60)
ms:contentKeyID: 62203338
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method

Gets the key for picking list entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As PickingList _
) As String
'Usage
Dim entity As PickingList
Dim returnValue As String

returnValue = Me.GetKey(entity)
```

``` csharp
protected override string GetKey(
    PickingList entity
)
```

``` c++
protected:
virtual String^ GetKey(
    PickingList^ entity
) override
```

#### Parameters

  - entity  
    Type: PickingList  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) key.  

## See Also

#### Reference

[PickingListsController Class](pickinglistscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

