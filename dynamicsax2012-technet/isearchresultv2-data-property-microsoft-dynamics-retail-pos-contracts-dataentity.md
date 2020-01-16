---
title: ISearchResultV2.Data Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Data Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResultV2.Data
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isearchresultv2.data(v=AX.60)
ms:contentKeyID: 62201995
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResultV2.Data
dev_langs:
- CSharp
- C++
- VB
---

# Data Property

Gets BarcodeInfo

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Data As Object
    Get
'Usage
Dim instance As ISearchResultV2
Dim value As Object

value = instance.Data
```

``` csharp
Object Data { get; }
```

``` c++
property Object^ Data {
    Object^ get ();
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## Remarks

This is specific to Kit Items from product details page.

## See Also

#### Reference

[ISearchResultV2 Interface](isearchresultv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

