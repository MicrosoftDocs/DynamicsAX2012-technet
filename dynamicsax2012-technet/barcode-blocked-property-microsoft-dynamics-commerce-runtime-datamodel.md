---
title: Barcode.Blocked Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Blocked Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.Blocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.blocked(v=AX.60)
ms:contentKeyID: 62206569
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.Blocked
dev_langs:
- CSharp
- C++
- VB
---

# Blocked Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Blocked As Boolean
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.Blocked

instance.Blocked = value
```

``` csharp
[DataMemberAttribute]
public bool Blocked { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool Blocked {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

