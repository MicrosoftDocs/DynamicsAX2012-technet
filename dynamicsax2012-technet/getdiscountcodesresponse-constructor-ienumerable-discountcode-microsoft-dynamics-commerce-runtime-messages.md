---
title: GetDiscountCodesResponse Constructor (IEnumerable(DiscountCode)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetDiscountCodesResponse Constructor (IEnumerable(DiscountCode))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDiscountCodesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getdiscountcodesresponse.getdiscountcodesresponse(v=AX.60)
ms:contentKeyID: 62215093
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDiscountCodesResponse Constructor (IEnumerable(DiscountCode))

Initializes a new instance of the [GetDiscountCodesResponse](getdiscountcodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    discountCodes As IEnumerable(Of DiscountCode) _
)
'Usage
Dim discountCodes As IEnumerable(Of DiscountCode)

Dim instance As New GetDiscountCodesResponse(discountCodes)
```

``` csharp
public GetDiscountCodesResponse(
    IEnumerable<DiscountCode> discountCodes
)
```

``` c++
public:
GetDiscountCodesResponse(
    IEnumerable<DiscountCode^>^ discountCodes
)
```

#### Parameters

  - discountCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetDiscountCodesResponse Class](getdiscountcodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetDiscountCodesResponse Overload](getdiscountcodesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

