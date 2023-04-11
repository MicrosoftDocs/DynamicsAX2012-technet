---
title: TaxableItem.BeginDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BeginDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.BeginDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.begindatetime(v=AX.60)
ms:contentKeyID: 49855228
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.BeginDateTime
dev_langs:
- CSharp
- C++
- VB
---

# BeginDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The start date and time of the transaction. Used for transaction/purchase date time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BeginDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As DateTimeOffset

value = instance.BeginDateTime

instance.BeginDateTime = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset BeginDateTime { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset BeginDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

