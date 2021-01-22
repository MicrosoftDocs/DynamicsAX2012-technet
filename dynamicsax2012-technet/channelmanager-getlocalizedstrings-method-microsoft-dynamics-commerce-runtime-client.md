---
title: ChannelManager.GetLocalizedStrings Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLocalizedStrings Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetLocalizedStrings(System.String,System.Nullable{System.Int32},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getlocalizedstrings(v=AX.60)
ms:contentKeyID: 65318545
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetLocalizedStrings
dev_langs:
- CSharp
- C++
- VB
---

# GetLocalizedStrings Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLocalizedStrings ( _
    languageId As String, _
    textId As Nullable(Of Integer), _
    settings As QueryResultSettings _
) As PagedResult(Of LocalizedString)
'Usage
Dim instance As ChannelManager
Dim languageId As String
Dim textId As Nullable(Of Integer)
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of LocalizedString)

returnValue = instance.GetLocalizedStrings(languageId, _
    textId, settings)
```

``` csharp
public PagedResult<LocalizedString> GetLocalizedStrings(
    string languageId,
    Nullable<int> textId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<LocalizedString^>^ GetLocalizedStrings(
    String^ languageId, 
    Nullable<int> textId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - textId  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[LocalizedString](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

