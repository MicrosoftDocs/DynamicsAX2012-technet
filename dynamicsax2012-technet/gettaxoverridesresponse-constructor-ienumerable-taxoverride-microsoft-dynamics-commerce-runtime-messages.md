---
title: GetTaxOverridesResponse Constructor (IEnumerable(TaxOverride)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetTaxOverridesResponse Constructor (IEnumerable(TaxOverride))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTaxOverridesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gettaxoverridesresponse.gettaxoverridesresponse(v=AX.60)
ms:contentKeyID: 62214142
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetTaxOverridesResponse Constructor (IEnumerable(TaxOverride))

Initializes a new instance of the [GetTaxOverridesResponse](gettaxoverridesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    taxOverrides As IEnumerable(Of TaxOverride) _
)
'Usage
Dim taxOverrides As IEnumerable(Of TaxOverride)

Dim instance As New GetTaxOverridesResponse(taxOverrides)
```

``` csharp
public GetTaxOverridesResponse(
    IEnumerable<TaxOverride> taxOverrides
)
```

``` c++
public:
GetTaxOverridesResponse(
    IEnumerable<TaxOverride^>^ taxOverrides
)
```

#### Parameters

  - taxOverrides  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetTaxOverridesResponse Class](gettaxoverridesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetTaxOverridesResponse Overload](gettaxoverridesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

