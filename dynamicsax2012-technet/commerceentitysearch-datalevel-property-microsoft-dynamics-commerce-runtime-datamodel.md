---
title: CommerceEntitySearch.DataLevel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataLevel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearch.DataLevel
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitysearch.datalevel(v=AX.60)
ms:contentKeyID: 62212492
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearch.DataLevel
dev_langs:
- CSharp
- C++
- VB
---

# DataLevel Property

Gets or sets the data level of the entity to be retrieved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property DataLevel As CommerceEntityDataLevel
    Get
    Set
'Usage
Dim instance As CommerceEntitySearch
Dim value As CommerceEntityDataLevel

value = instance.DataLevel

instance.DataLevel = value
```

``` csharp
[IgnoreDataMemberAttribute]
public CommerceEntityDataLevel DataLevel { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property CommerceEntityDataLevel DataLevel {
    CommerceEntityDataLevel get ();
    void set (CommerceEntityDataLevel value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel](commerceentitydatalevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The data level to be retrieved.  

## See Also

#### Reference

[CommerceEntitySearch Class](commerceentitysearch-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

