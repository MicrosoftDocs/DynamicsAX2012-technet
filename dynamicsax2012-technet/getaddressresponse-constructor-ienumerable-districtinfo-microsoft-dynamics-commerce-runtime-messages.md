---
title: GetAddressResponse Constructor (IEnumerable(DistrictInfo)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAddressResponse Constructor (IEnumerable(DistrictInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DistrictInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.getaddressresponse(v=AX.60)
ms:contentKeyID: 62201768
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressResponse Constructor (IEnumerable(DistrictInfo))

Initializes a new instance of the [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    districts As IEnumerable(Of DistrictInfo) _
)
'Usage
Dim districts As IEnumerable(Of DistrictInfo)

Dim instance As New GetAddressResponse(districts)
```

``` csharp
public GetAddressResponse(
    IEnumerable<DistrictInfo> districts
)
```

``` c++
public:
GetAddressResponse(
    IEnumerable<DistrictInfo^>^ districts
)
```

#### Parameters

  - districts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DistrictInfo](districtinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAddressResponse Overload](getaddressresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

