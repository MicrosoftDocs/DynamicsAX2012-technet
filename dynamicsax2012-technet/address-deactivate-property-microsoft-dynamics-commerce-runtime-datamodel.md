---
title: Address.Deactivate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Deactivate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Deactivate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.deactivate(v=AX.60)
ms:contentKeyID: 62212925
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.Deactivate
dev_langs:
- CSharp
- C++
- VB
---

# Deactivate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this address will be deactivated or not upon save.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Deactivate As Boolean
    Get
    Set
'Usage
Dim instance As Address
Dim value As Boolean

value = instance.Deactivate

instance.Deactivate = value
```

``` csharp
[DataMemberAttribute]
public bool Deactivate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool Deactivate {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

