---
title: TenderType.MinimumSignatureCaptureAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumSignatureCaptureAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumSignatureCaptureAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.minimumsignaturecaptureamount(v=AX.60)
ms:contentKeyID: 62202007
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumSignatureCaptureAmount
dev_langs:
- CSharp
- C++
- VB
---

# MinimumSignatureCaptureAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the minimum signature capture amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MINIMUMSIGNATURECAPTUREAMOUNT")> _
Public Property MinimumSignatureCaptureAmount As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MinimumSignatureCaptureAmount

instance.MinimumSignatureCaptureAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MINIMUMSIGNATURECAPTUREAMOUNT")]
public decimal MinimumSignatureCaptureAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MINIMUMSIGNATURECAPTUREAMOUNT")]
public:
property Decimal MinimumSignatureCaptureAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

