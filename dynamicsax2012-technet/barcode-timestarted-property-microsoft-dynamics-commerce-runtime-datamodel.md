---
title: Barcode.TimeStarted Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeStarted Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.TimeStarted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.timestarted(v=AX.60)
ms:contentKeyID: 62209576
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.TimeStarted
dev_langs:
- CSharp
- C++
- VB
---

# TimeStarted Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TimeStarted As DateTimeOffset
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As DateTimeOffset

value = instance.TimeStarted

instance.TimeStarted = value
```

``` csharp
[IgnoreDataMemberAttribute]
public DateTimeOffset TimeStarted { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property DateTimeOffset TimeStarted {
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

