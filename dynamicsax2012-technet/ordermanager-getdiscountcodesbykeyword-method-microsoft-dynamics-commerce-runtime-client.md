---
title: OrderManager.GetDiscountCodesByKeyword Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDiscountCodesByKeyword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodesByKeyword(System.String,System.DateTime,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getdiscountcodesbykeyword(v=AX.60)
ms:contentKeyID: 65320742
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodesByKeyword
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodesByKeyword Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDiscountCodesByKeyword ( _
    keyword As String, _
    activeDate As DateTime, _
    settings As QueryResultSettings _
) As PagedResult(Of DiscountCode)
'Usage
Dim instance As OrderManager
Dim keyword As String
Dim activeDate As DateTime
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of DiscountCode)

returnValue = instance.GetDiscountCodesByKeyword(keyword, _
    activeDate, settings)
```

``` csharp
public PagedResult<DiscountCode> GetDiscountCodesByKeyword(
    string keyword,
    DateTime activeDate,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<DiscountCode^>^ GetDiscountCodesByKeyword(
    String^ keyword, 
    DateTime activeDate, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - keyword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

