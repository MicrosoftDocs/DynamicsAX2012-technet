---
title: Barcode.TimeFinished Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeFinished Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.TimeFinished
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.timefinished(v=AX.60)
ms:contentKeyID: 62202092
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.TimeFinished
dev_langs:
- CSharp
- C++
- VB
---

# TimeFinished Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TimeFinished As DateTimeOffset
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As DateTimeOffset

value = instance.TimeFinished

instance.TimeFinished = value
```

``` csharp
[IgnoreDataMemberAttribute]
public DateTimeOffset TimeFinished { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property DateTimeOffset TimeFinished {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

