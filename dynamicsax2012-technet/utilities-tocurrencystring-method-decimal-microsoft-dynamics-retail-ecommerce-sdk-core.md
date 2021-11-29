---
title: Utilities.ToCurrencyString Method (Decimal) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: ToCurrencyString Method (Decimal)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Utilities.ToCurrencyString(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.utilities.tocurrencystring(v=AX.60)
ms:contentKeyID: 65318502
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ToCurrencyString Method (Decimal)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToCurrencyString ( _
    amount As Decimal _
) As String
'Usage
Dim amount As Decimal
Dim returnValue As String

returnValue = amount.ToCurrencyString()
```

``` csharp
public static string ToCurrencyString(
    this decimal amount
)
```

``` c++
[ExtensionAttribute]
public:
static String^ ToCurrencyString(
    Decimal amount
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[ToCurrencyString Overload](utilities-tocurrencystring-method-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

