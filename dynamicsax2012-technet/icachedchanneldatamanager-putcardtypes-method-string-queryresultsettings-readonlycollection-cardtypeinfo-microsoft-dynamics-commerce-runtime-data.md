---
title: ICachedChannelDataManager.PutCardTypes Method (String, QueryResultSettings, ReadOnlyCollection(CardTypeInfo)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutCardTypes Method (String, QueryResultSettings, ReadOnlyCollection(CardTypeInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutCardTypes(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putcardtypes(v=AX.60)
ms:contentKeyID: 65319330
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutCardTypes Method (String, QueryResultSettings, ReadOnlyCollection(CardTypeInfo))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutCardTypes ( _
    name As String, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of CardTypeInfo) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim name As String
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of CardTypeInfo)

instance.PutCardTypes(name, settings, _
    result)
```

``` csharp
void PutCardTypes(
    string name,
    QueryResultSettings settings,
    ReadOnlyCollection<CardTypeInfo> result
)
```

``` c++
void PutCardTypes(
    String^ name, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<CardTypeInfo^>^ result
)
```

#### Parameters

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[PutCardTypes Overload](icachedchanneldatamanager-putcardtypes-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

