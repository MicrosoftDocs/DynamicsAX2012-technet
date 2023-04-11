---
title: ChannelDataManager.GetPictureByPictureId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPictureByPictureId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetPictureByPictureId(System.Int32,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getpicturebypictureid(v=AX.60)
ms:contentKeyID: 65315826
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetPictureByPictureId
dev_langs:
- CSharp
- C++
- VB
---

# GetPictureByPictureId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetPictureByPictureId ( _
    pictureId As Integer, _
    settings As QueryResultSettings _
) As RetailImage
'Usage
Dim instance As ChannelDataManager
Dim pictureId As Integer
Dim settings As QueryResultSettings
Dim returnValue As RetailImage

returnValue = instance.GetPictureByPictureId(pictureId, _
    settings)
```

``` csharp
public RetailImage GetPictureByPictureId(
    int pictureId,
    QueryResultSettings settings
)
```

``` c++
public:
virtual RetailImage^ GetPictureByPictureId(
    int pictureId, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - pictureId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage](retailimage-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[IChannelDataManager.GetPictureByPictureId(Int32, QueryResultSettings)](ichanneldatamanager-getpicturebypictureid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

