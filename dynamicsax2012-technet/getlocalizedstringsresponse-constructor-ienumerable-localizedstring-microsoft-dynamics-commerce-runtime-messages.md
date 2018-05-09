---
title: GetLocalizedStringsResponse Constructor (IEnumerable(LocalizedString)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetLocalizedStringsResponse Constructor (IEnumerable(LocalizedString))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getlocalizedstringsresponse.getlocalizedstringsresponse(v=AX.60)
ms:contentKeyID: 62215073
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetLocalizedStringsResponse Constructor (IEnumerable(LocalizedString))

Initializes a new instance of the [GetLocalizedStringsResponse](getlocalizedstringsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    localizedStrings As IEnumerable(Of LocalizedString) _
)
'Usage
Dim localizedStrings As IEnumerable(Of LocalizedString)

Dim instance As New GetLocalizedStringsResponse(localizedStrings)
```

``` csharp
public GetLocalizedStringsResponse(
    IEnumerable<LocalizedString> localizedStrings
)
```

``` c++
public:
GetLocalizedStringsResponse(
    IEnumerable<LocalizedString^>^ localizedStrings
)
```

#### Parameters

  - localizedStrings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[LocalizedString](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLocalizedStringsResponse Class](getlocalizedstringsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetLocalizedStringsResponse Overload](getlocalizedstringsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

