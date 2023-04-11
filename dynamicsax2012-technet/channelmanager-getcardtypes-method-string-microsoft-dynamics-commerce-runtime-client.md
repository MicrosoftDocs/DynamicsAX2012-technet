---
title: ChannelManager.GetCardTypes Method (String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCardTypes Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetCardTypes(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getcardtypes(v=AX.60)
ms:contentKeyID: 62205742
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardTypes Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the list of card types that match specified card number or all types if card number is not specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCardTypes ( _
    cardNumber As String _
) As PagedResult(Of CardTypeInfo)
'Usage
Dim instance As ChannelManager
Dim cardNumber As String
Dim returnValue As PagedResult(Of CardTypeInfo)

returnValue = instance.GetCardTypes(cardNumber)
```

``` csharp
public PagedResult<CardTypeInfo> GetCardTypes(
    string cardNumber
)
```

``` c++
public:
PagedResult<CardTypeInfo^>^ GetCardTypes(
    String^ cardNumber
)
```

#### Parameters

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns card type collection.  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetCardTypes Overload](channelmanager-getcardtypes-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

