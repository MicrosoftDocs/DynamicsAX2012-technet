---
title: PriceChangedNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceChangedNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceChangedNotification.#ctor(System.String,System.Decimal,System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricechangednotification.pricechangednotification(v=AX.60)
ms:contentKeyID: 65319298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceChangedNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PriceChangedNotification Constructor

Initializes a new instance of the [PriceChangedNotification](pricechangednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    oldPrice As Decimal, _
    newPrice As Decimal, _
    inventDimId As String _
)
'Usage
Dim itemId As String
Dim oldPrice As Decimal
Dim newPrice As Decimal
Dim inventDimId As String

Dim instance As New PriceChangedNotification(itemId, _
    oldPrice, newPrice, inventDimId)
```

``` csharp
public PriceChangedNotification(
    string itemId,
    decimal oldPrice,
    decimal newPrice,
    string inventDimId
)
```

``` c++
public:
PriceChangedNotification(
    String^ itemId, 
    Decimal oldPrice, 
    Decimal newPrice, 
    String^ inventDimId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - oldPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - newPrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[PriceChangedNotification Class](pricechangednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

