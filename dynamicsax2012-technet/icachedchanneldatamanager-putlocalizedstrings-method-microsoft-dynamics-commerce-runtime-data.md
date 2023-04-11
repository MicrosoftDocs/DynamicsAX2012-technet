---
title: ICachedChannelDataManager.PutLocalizedStrings Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutLocalizedStrings Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutLocalizedStrings(System.String,System.Nullable{System.Int32},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putlocalizedstrings(v=AX.60)
ms:contentKeyID: 65321374
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutLocalizedStrings
dev_langs:
- CSharp
- C++
- VB
---

# PutLocalizedStrings Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutLocalizedStrings ( _
    languageId As String, _
    textId As Nullable(Of Integer), _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of LocalizedString) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim languageId As String
Dim textId As Nullable(Of Integer)
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of LocalizedString)

instance.PutLocalizedStrings(languageId, _
    textId, settings, result)
```

``` csharp
void PutLocalizedStrings(
    string languageId,
    Nullable<int> textId,
    QueryResultSettings settings,
    ReadOnlyCollection<LocalizedString> result
)
```

``` c++
void PutLocalizedStrings(
    String^ languageId, 
    Nullable<int> textId, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<LocalizedString^>^ result
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

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LocalizedString](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

