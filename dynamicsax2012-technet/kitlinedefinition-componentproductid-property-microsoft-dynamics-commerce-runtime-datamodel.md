---
title: KitLineDefinition.ComponentProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ComponentProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.ComponentProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlinedefinition.componentproductid(v=AX.60)
ms:contentKeyID: 62204976
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition.ComponentProductId
dev_langs:
- CSharp
- C++
- VB
---

# ComponentProductId Property

Gets the product Id that is used as a default component in the current kit component definition.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ComponentProductId As Long
    Get
    Set
'Usage
Dim instance As KitLineDefinition
Dim value As Long

value = instance.ComponentProductId

instance.ComponentProductId = value
```

``` csharp
[DataMemberAttribute]
public long ComponentProductId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ComponentProductId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitLineDefinition Class](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

