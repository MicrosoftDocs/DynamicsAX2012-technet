---
title: UnitOfMeasureConversion.ProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.ProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.productrecordid(v=AX.60)
ms:contentKeyID: 49834810
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.ProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier of the product for this unit of measure conversion.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRODUCT")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("PRODUCT")> _
Public Property ProductRecordId As Long
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Long

value = instance.ProductRecordId

instance.ProductRecordId = value
```

``` csharp
[ColumnAttribute("PRODUCT")]
[DataMemberAttribute]
[ReadOnlyAttribute("PRODUCT")]
public long ProductRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"PRODUCT")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"PRODUCT")]
public:
property long long ProductRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## Remarks

This is the RecId of the EcoResProduct table.

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

