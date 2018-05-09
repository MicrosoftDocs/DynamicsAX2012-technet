---
title: IItemV1.ItemSearch Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ItemSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV1.ItemSearch(System.String@,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iitemv1.itemsearch(v=AX.60)
ms:contentKeyID: 47344363
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV1.ItemSearch
dev_langs:
- CSharp
- C++
- VB
---

# ItemSearch Method

Displays the Item Search dialog.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ItemSearch ( _
    ByRef selectedItemId As String, _
    numberOfDisplayedRows As Integer _
) As Boolean
'Usage
Dim instance As IItemV1
Dim selectedItemId As String
Dim numberOfDisplayedRows As Integer
Dim returnValue As Boolean

returnValue = instance.ItemSearch(selectedItemId, _
    numberOfDisplayedRows)
```

``` csharp
bool ItemSearch(
    ref string selectedItemId,
    int numberOfDisplayedRows
)
```

``` c++
bool ItemSearch(
    String^% selectedItemId, 
    int numberOfDisplayedRows
)
```

#### Parameters

  - selectedItemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - numberOfDisplayedRows  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
false if the user pressed cancel; othewrwise, true.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

