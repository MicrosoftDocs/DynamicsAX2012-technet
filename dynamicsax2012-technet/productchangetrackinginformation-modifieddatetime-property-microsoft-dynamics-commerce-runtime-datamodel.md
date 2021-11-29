---
title: ProductChangeTrackingInformation.ModifiedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ModifiedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.ModifiedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinginformation.modifieddatetime(v=AX.60)
ms:contentKeyID: 62212317
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.ModifiedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# ModifiedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the date this product was last changed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ModifiedDateTime As DateTimeOffset
    Get
    Private Set
'Usage
Dim instance As ProductChangeTrackingInformation
Dim value As DateTimeOffset

value = instance.ModifiedDateTime
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset ModifiedDateTime { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset ModifiedDateTime {
    DateTimeOffset get ();
    private: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingInformation Class](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

