---
title: ChannelDatabaseAccessor.GetDirectChildCategories Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDirectChildCategories Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetDirectChildCategories(System.Int64,System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getdirectchildcategories(v=AX.60)
ms:contentKeyID: 65316856
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetDirectChildCategories
dev_langs:
- CSharp
- C++
- VB
---

# GetDirectChildCategories Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetDirectChildCategories ( _
    channelId As Long, _
    parentCategoryId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Category)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim channelId As Long
Dim parentCategoryId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Category)

returnValue = instance.GetDirectChildCategories(channelId, _
    parentCategoryId, settings)
```

``` csharp
public ReadOnlyCollection<Category> GetDirectChildCategories(
    long channelId,
    long parentCategoryId,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<Category^>^ GetDirectChildCategories(
    long long channelId, 
    long long parentCategoryId, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parentCategoryId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IChannelDataManager.GetDirectChildCategories(Int64, Int64, QueryResultSettings)](ichanneldatamanager-getdirectchildcategories-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

