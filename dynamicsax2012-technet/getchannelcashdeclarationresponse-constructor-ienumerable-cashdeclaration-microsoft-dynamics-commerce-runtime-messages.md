---
title: GetChannelCashDeclarationResponse Constructor (IEnumerable(CashDeclaration)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelCashDeclarationResponse Constructor (IEnumerable(CashDeclaration))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCashDeclarationResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CashDeclaration})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcashdeclarationresponse.getchannelcashdeclarationresponse(v=AX.60)
ms:contentKeyID: 62206443
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelCashDeclarationResponse Constructor (IEnumerable(CashDeclaration))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetChannelCashDeclarationResponse](getchannelcashdeclarationresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cashDeclarations As IEnumerable(Of CashDeclaration) _
)
'Usage
Dim cashDeclarations As IEnumerable(Of CashDeclaration)

Dim instance As New GetChannelCashDeclarationResponse(cashDeclarations)
```

``` csharp
public GetChannelCashDeclarationResponse(
    IEnumerable<CashDeclaration> cashDeclarations
)
```

``` c++
public:
GetChannelCashDeclarationResponse(
    IEnumerable<CashDeclaration^>^ cashDeclarations
)
```

#### Parameters

  - cashDeclarations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CashDeclaration](cashdeclaration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelCashDeclarationResponse Class](getchannelcashdeclarationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelCashDeclarationResponse Overload](getchannelcashdeclarationresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

