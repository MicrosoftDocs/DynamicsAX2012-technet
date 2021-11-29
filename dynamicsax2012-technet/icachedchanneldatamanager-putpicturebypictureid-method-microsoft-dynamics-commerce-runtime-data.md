---
title: ICachedChannelDataManager.PutPictureByPictureId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPictureByPictureId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutPictureByPictureId(System.Int32,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putpicturebypictureid(v=AX.60)
ms:contentKeyID: 65321265
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutPictureByPictureId
dev_langs:
- CSharp
- C++
- VB
---

# PutPictureByPictureId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPictureByPictureId ( _
    pictureId As Integer, _
    settings As QueryResultSettings, _
    result As RetailImage _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim pictureId As Integer
Dim settings As QueryResultSettings
Dim result As RetailImage

instance.PutPictureByPictureId(pictureId, _
    settings, result)
```

``` csharp
void PutPictureByPictureId(
    int pictureId,
    QueryResultSettings settings,
    RetailImage result
)
```

``` c++
void PutPictureByPictureId(
    int pictureId, 
    QueryResultSettings^ settings, 
    RetailImage^ result
)
```

#### Parameters

  - pictureId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage](retailimage-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

