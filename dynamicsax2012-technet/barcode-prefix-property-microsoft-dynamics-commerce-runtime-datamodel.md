---
title: Barcode.Prefix Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Prefix Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.Prefix
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.prefix(v=AX.60)
ms:contentKeyID: 62204764
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.Prefix
dev_langs:
- CSharp
- C++
- VB
---

# Prefix Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Prefix As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.Prefix

instance.Prefix = value
```

``` csharp
[DataMemberAttribute]
public string Prefix { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Prefix {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

