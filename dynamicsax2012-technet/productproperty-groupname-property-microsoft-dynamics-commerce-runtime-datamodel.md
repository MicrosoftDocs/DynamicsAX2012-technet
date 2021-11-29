---
title: ProductProperty.GroupName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GroupName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.groupname(v=AX.60)
ms:contentKeyID: 62212402
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupName
dev_langs:
- CSharp
- C++
- VB
---

# GroupName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the underlying attribute's group name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GroupName As String
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As String

value = instance.GroupName

instance.GroupName = value
```

``` csharp
[DataMemberAttribute]
public string GroupName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ GroupName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

