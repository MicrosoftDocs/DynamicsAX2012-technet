---
title: ProductIdentity.LookupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LookupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.LookupId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.lookupid(v=AX.60)
ms:contentKeyID: 62208011
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.LookupId
dev_langs:
- CSharp
- C++
- VB
---

# LookupId Property

Gets the product lookup identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOOKUPID")> _
Public Property LookupId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As Long

value = instance.LookupId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOOKUPID")]
public long LookupId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOOKUPID")]
public:
property long long LookupId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

