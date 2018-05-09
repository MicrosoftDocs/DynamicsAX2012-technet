---
title: KitConfigToComponentAssociation.KitProductMasterId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitProductMasterId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitProductMasterId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation.kitproductmasterid(v=AX.60)
ms:contentKeyID: 65316211
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation.KitProductMasterId
dev_langs:
- CSharp
- C++
- VB
---

# KitProductMasterId Property

Gets the Kit's product master identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KITPRODUCTMASTERLISTING")> _
Public Property KitProductMasterId As Long
    Get
    Friend Set
'Usage
Dim instance As KitConfigToComponentAssociation
Dim value As Long

value = instance.KitProductMasterId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KITPRODUCTMASTERLISTING")]
public long KitProductMasterId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KITPRODUCTMASTERLISTING")]
public:
property long long KitProductMasterId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitConfigToComponentAssociation Class](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

