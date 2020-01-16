---
title: GetItemDeliveryOptionsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetItemDeliveryOptionsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.#ctor(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemdeliveryoptionsdatarequest.getitemdeliveryoptionsdatarequest(v=AX.60)
ms:contentKeyID: 65320311
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemDeliveryOptionsDataRequest Constructor

Initializes a new instance of the [GetItemDeliveryOptionsDataRequest](getitemdeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    variantInventoryDimensionId As String, _
    countryRegionId As String, _
    stateId As String _
)
'Usage
Dim itemId As String
Dim variantInventoryDimensionId As String
Dim countryRegionId As String
Dim stateId As String

Dim instance As New GetItemDeliveryOptionsDataRequest(itemId, _
    variantInventoryDimensionId, countryRegionId, _
    stateId)
```

``` csharp
public GetItemDeliveryOptionsDataRequest(
    string itemId,
    string variantInventoryDimensionId,
    string countryRegionId,
    string stateId
)
```

``` c++
public:
GetItemDeliveryOptionsDataRequest(
    String^ itemId, 
    String^ variantInventoryDimensionId, 
    String^ countryRegionId, 
    String^ stateId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantInventoryDimensionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - countryRegionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetItemDeliveryOptionsDataRequest Class](getitemdeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

