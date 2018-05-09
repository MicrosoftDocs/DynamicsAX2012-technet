---
title: Barcode.DateToBeBlocked Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateToBeBlocked Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.DateToBeBlocked
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.datetobeblocked(v=AX.60)
ms:contentKeyID: 62205506
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.DateToBeBlocked
dev_langs:
- CSharp
- C++
- VB
---

# DateToBeBlocked Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DateToBeBlocked As DateTimeOffset
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As DateTimeOffset

value = instance.DateToBeBlocked

instance.DateToBeBlocked = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset DateToBeBlocked { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset DateToBeBlocked {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

