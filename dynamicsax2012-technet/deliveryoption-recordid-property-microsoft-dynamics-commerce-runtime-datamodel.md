---
title: DeliveryOption.RecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.RecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deliveryoption.recordid(v=AX.60)
ms:contentKeyID: 49853101
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.RecordId
dev_langs:
- CSharp
- C++
- VB
---

# RecordId Property

Gets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<KeyAttribute> _
<ColumnAttribute("RECID")> _
<DataMemberAttribute> _
Public Property RecordId As Long
    Get
    Friend Set
'Usage
Dim instance As DeliveryOption
Dim value As Long

value = instance.RecordId
```

``` csharp
[KeyAttribute]
[ColumnAttribute("RECID")]
[DataMemberAttribute]
public long RecordId { get; internal set; }
```

``` c++
[KeyAttribute]
[ColumnAttribute(L"RECID")]
[DataMemberAttribute]
public:
property long long RecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[DeliveryOption Class](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

