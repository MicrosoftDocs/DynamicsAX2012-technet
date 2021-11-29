---
title: ISearchResultV1.SearchType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SearchType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResultV1.SearchType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isearchresultv1.searchtype(v=AX.60)
ms:contentKeyID: 49821782
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISearchResultV1.SearchType
dev_langs:
- CSharp
- C++
- VB
---

# SearchType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type of the search result.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SearchType As SearchResultType
    Get
'Usage
Dim instance As ISearchResultV1
Dim value As SearchResultType

value = instance.SearchType
```

``` csharp
SearchResultType SearchType { get; }
```

``` c++
property SearchResultType SearchType {
    SearchResultType get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.SearchResultType](searchresulttype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [SearchResultType](searchresulttype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ISearchResultV1 Interface](isearchresultv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

