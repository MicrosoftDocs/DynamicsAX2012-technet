---
title: ChannelManager.GetLocalizedStringsForLanguage Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLocalizedStringsForLanguage Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetLocalizedStringsForLanguage(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getlocalizedstringsforlanguage(v=AX.60)
ms:contentKeyID: 65319104
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetLocalizedStringsForLanguage
dev_langs:
- CSharp
- C++
- VB
---

# GetLocalizedStringsForLanguage Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLocalizedStringsForLanguage ( _
    languageId As String, _
    settings As QueryResultSettings _
) As PagedResult(Of LocalizedString)
'Usage
Dim instance As ChannelManager
Dim languageId As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of LocalizedString)

returnValue = instance.GetLocalizedStringsForLanguage(languageId, _
    settings)
```

``` csharp
public PagedResult<LocalizedString> GetLocalizedStringsForLanguage(
    string languageId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<LocalizedString^>^ GetLocalizedStringsForLanguage(
    String^ languageId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LocalizedString](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

