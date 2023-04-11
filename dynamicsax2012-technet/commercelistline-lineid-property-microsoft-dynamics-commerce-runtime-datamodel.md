---
title: CommerceListLine.LineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.LineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelistline.lineid(v=AX.60)
ms:contentKeyID: 62214538
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.LineId
dev_langs:
- CSharp
- C++
- VB
---

# LineId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list line identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineId As String
    Get
    Set
'Usage
Dim instance As CommerceListLine
Dim value As String

value = instance.LineId

instance.LineId = value
```

``` csharp
[DataMemberAttribute]
public string LineId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LineId {
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

