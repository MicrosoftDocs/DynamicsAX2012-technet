---
title: TaxableItem.EndDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EndDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.EndDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.enddatetime(v=AX.60)
ms:contentKeyID: 49832747
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.EndDateTime
dev_langs:
- CSharp
- C++
- VB
---

# EndDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The end date and time of the transaction. Used for returned orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EndDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As DateTimeOffset

value = instance.EndDateTime

instance.EndDateTime = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset EndDateTime { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset EndDateTime {
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

