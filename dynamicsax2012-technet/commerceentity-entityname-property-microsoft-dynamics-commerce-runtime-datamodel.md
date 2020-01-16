---
title: CommerceEntity.EntityName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntityName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.EntityName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentity.entityname(v=AX.60)
ms:contentKeyID: 49832380
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.EntityName
dev_langs:
- CSharp
- C++
- VB
---

# EntityName Property

Gets the name of the entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property EntityName As String
    Get
    Set
'Usage
Dim instance As CommerceEntity
Dim value As String

value = instance.EntityName

instance.EntityName = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string EntityName { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ EntityName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name of the entity.  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

