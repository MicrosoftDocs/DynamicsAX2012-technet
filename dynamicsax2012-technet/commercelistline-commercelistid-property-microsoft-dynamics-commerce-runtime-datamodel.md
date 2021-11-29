---
title: CommerceListLine.CommerceListId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceListId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.CommerceListId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelistline.commercelistid(v=AX.60)
ms:contentKeyID: 62201916
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.CommerceListId
dev_langs:
- CSharp
- C++
- VB
---

# CommerceListId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceListId As String
    Get
    Set
'Usage
Dim instance As CommerceListLine
Dim value As String

value = instance.CommerceListId

instance.CommerceListId = value
```

``` csharp
[DataMemberAttribute]
public string CommerceListId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CommerceListId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceListLine Class](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

