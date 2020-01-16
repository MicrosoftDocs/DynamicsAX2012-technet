---
title: MissingLineShippingInfoNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MissingLineShippingInfoNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification.#ctor(System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.missinglineshippinginfonotification.missinglineshippinginfonotification(v=AX.60)
ms:contentKeyID: 65322340
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.MissingLineShippingInfoNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# MissingLineShippingInfoNotification Constructor

Initializes a new instance of the [MissingLineShippingInfoNotification](missinglineshippinginfonotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    lineIdsWithMissingDeliveryMode As IEnumerable(Of String), _
    lineIdsWithMissingInventoryLocation As IEnumerable(Of String), _
    lineIdsWithMissingShippingAddress As IEnumerable(Of String) _
)
'Usage
Dim lineIdsWithMissingDeliveryMode As IEnumerable(Of String)
Dim lineIdsWithMissingInventoryLocation As IEnumerable(Of String)
Dim lineIdsWithMissingShippingAddress As IEnumerable(Of String)

Dim instance As New MissingLineShippingInfoNotification(lineIdsWithMissingDeliveryMode, _
    lineIdsWithMissingInventoryLocation, _
    lineIdsWithMissingShippingAddress)
```

``` csharp
public MissingLineShippingInfoNotification(
    IEnumerable<string> lineIdsWithMissingDeliveryMode,
    IEnumerable<string> lineIdsWithMissingInventoryLocation,
    IEnumerable<string> lineIdsWithMissingShippingAddress
)
```

``` c++
public:
MissingLineShippingInfoNotification(
    IEnumerable<String^>^ lineIdsWithMissingDeliveryMode, 
    IEnumerable<String^>^ lineIdsWithMissingInventoryLocation, 
    IEnumerable<String^>^ lineIdsWithMissingShippingAddress
)
```

#### Parameters

  - lineIdsWithMissingDeliveryMode  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - lineIdsWithMissingInventoryLocation  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - lineIdsWithMissingShippingAddress  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[MissingLineShippingInfoNotification Class](missinglineshippinginfonotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

