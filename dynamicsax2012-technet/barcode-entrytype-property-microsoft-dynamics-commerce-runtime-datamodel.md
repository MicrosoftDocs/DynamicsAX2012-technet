---
title: Barcode.EntryType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.entrytype(v=AX.60)
ms:contentKeyID: 62210430
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property EntryType As Integer
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Integer

value = instance.EntryType

instance.EntryType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public int EntryType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property int EntryType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

