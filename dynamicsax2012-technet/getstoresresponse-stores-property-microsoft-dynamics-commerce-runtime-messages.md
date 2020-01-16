---
title: GetStoresResponse.Stores Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoresresponse.stores(v=AX.60)
ms:contentKeyID: 62213329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresResponse.Stores
dev_langs:
- CSharp
- C++
- VB
---

# Stores Property

Gets the Shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Stores As PagedResult(Of OrgUnit)
    Get
    Private Set
'Usage
Dim instance As GetStoresResponse
Dim value As PagedResult(Of OrgUnit)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public PagedResult<OrgUnit> Stores { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PagedResult<OrgUnit^>^ Stores {
    PagedResult<OrgUnit^>^ get ();
    private: void set (PagedResult<OrgUnit^>^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [PagedResult\<TEntity\>](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[GetStoresResponse Class](getstoresresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

