---
title: OrderManager.GetDiscountCodeDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDiscountCodeDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodeDetails(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getdiscountcodedetails(v=AX.60)
ms:contentKeyID: 62213888
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodeDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodeDetails Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the discount code details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDiscountCodeDetails ( _
    discountCode As String _
) As DiscountCode
'Usage
Dim instance As OrderManager
Dim discountCode As String
Dim returnValue As DiscountCode

returnValue = instance.GetDiscountCodeDetails(discountCode)
```

``` csharp
public DiscountCode GetDiscountCodeDetails(
    string discountCode
)
```

``` c++
public:
DiscountCode^ GetDiscountCodeDetails(
    String^ discountCode
)
```

#### Parameters

  - discountCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The discount code details.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

