---
title: InvalidPriceNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvalidPriceNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidPriceNotification.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.invalidpricenotification.invalidpricenotification(v=AX.60)
ms:contentKeyID: 65321228
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidPriceNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# InvalidPriceNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [InvalidPriceNotification](invalidpricenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    inventDimId As String _
)
'Usage
Dim itemId As String
Dim inventDimId As String

Dim instance As New InvalidPriceNotification(itemId, _
    inventDimId)
```

``` csharp
public InvalidPriceNotification(
    string itemId,
    string inventDimId
)
```

``` c++
public:
InvalidPriceNotification(
    String^ itemId, 
    String^ inventDimId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[InvalidPriceNotification Class](invalidpricenotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

