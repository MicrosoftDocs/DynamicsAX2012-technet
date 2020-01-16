---
title: GetSupportedLanguagesResponse Constructor (IEnumerable(SupportedLanguage)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetSupportedLanguagesResponse Constructor (IEnumerable(SupportedLanguage))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SupportedLanguage})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getsupportedlanguagesresponse.getsupportedlanguagesresponse(v=AX.60)
ms:contentKeyID: 62213192
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSupportedLanguagesResponse Constructor (IEnumerable(SupportedLanguage))

Initializes a new instance of the [GetSupportedLanguagesResponse](getsupportedlanguagesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    languages As IEnumerable(Of SupportedLanguage) _
)
'Usage
Dim languages As IEnumerable(Of SupportedLanguage)

Dim instance As New GetSupportedLanguagesResponse(languages)
```

``` csharp
public GetSupportedLanguagesResponse(
    IEnumerable<SupportedLanguage> languages
)
```

``` c++
public:
GetSupportedLanguagesResponse(
    IEnumerable<SupportedLanguage^>^ languages
)
```

#### Parameters

  - languages  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SupportedLanguage](supportedlanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetSupportedLanguagesResponse Class](getsupportedlanguagesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetSupportedLanguagesResponse Overload](getsupportedlanguagesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

