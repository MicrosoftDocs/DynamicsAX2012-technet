---
title: ChannelDataManager.GetLocalizedStrings Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLocalizedStrings Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetLocalizedStrings(System.String,System.Nullable{System.Int32},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getlocalizedstrings(v=AX.60)
ms:contentKeyID: 65320930
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetLocalizedStrings
dev_langs:
- CSharp
- C++
- VB
---

# GetLocalizedStrings Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLocalizedStrings ( _
    languageId As String, _
    textId As Nullable(Of Integer), _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of LocalizedString)
'Usage
Dim instance As ChannelDataManager
Dim languageId As String
Dim textId As Nullable(Of Integer)
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of LocalizedString)

returnValue = instance.GetLocalizedStrings(languageId, _
    textId, settings)
```

``` csharp
public ReadOnlyCollection<LocalizedString> GetLocalizedStrings(
    string languageId,
    Nullable<int> textId,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<LocalizedString^>^ GetLocalizedStrings(
    String^ languageId, 
    Nullable<int> textId, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - textId  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LocalizedString](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetLocalizedStrings(String, Nullable\<Int32\>, QueryResultSettings)](ichanneldatamanager-getlocalizedstrings-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

