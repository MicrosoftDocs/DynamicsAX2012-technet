---
title: GetActiveProductPriceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetActiveProductPriceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceResponse
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getactiveproductpriceresponse(v=AX.60)
ms:contentKeyID: 62207939
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveProductPriceResponse Class

Response from getting the active product prices for items.

This contains three prices for an item: Base Price: Base sales price on an item Trade Agreement Price: Price defined by trade agreements Price Adjustment Price: Price defined by price adjustments, if better than trade agreements.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class GetActiveProductPriceResponse _
    Inherits Response
'Usage
Dim instance As GetActiveProductPriceResponse
```

``` csharp
[DataContractAttribute]
public sealed class GetActiveProductPriceResponse : Response
```

``` c++
[DataContractAttribute]
public ref class GetActiveProductPriceResponse sealed : public Response
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

