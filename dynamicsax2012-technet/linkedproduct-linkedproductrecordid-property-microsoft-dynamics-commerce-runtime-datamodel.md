---
title: LinkedProduct.LinkedProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LinkedProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct.LinkedProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linkedproduct.linkedproductrecordid(v=AX.60)
ms:contentKeyID: 62213142
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct.LinkedProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LinkedProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the linked Product record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINKEDPRODUCT")> _
Public Property LinkedProductRecordId As Long
    Get
    Set
'Usage
Dim instance As LinkedProduct
Dim value As Long

value = instance.LinkedProductRecordId

instance.LinkedProductRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINKEDPRODUCT")]
public long LinkedProductRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINKEDPRODUCT")]
public:
property long long LinkedProductRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LinkedProduct Class](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

