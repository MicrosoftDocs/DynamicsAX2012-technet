---
title: IChannelDataManager.GetPictureByPictureId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPictureByPictureId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetPictureByPictureId(System.Int32,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getpicturebypictureid(v=AX.60)
ms:contentKeyID: 65315555
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetPictureByPictureId
dev_langs:
- CSharp
- C++
- VB
---

# GetPictureByPictureId Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetPictureByPictureId ( _
    pictureId As Integer, _
    settings As QueryResultSettings _
) As RetailImage
'Usage
Dim instance As IChannelDataManager
Dim pictureId As Integer
Dim settings As QueryResultSettings
Dim returnValue As RetailImage

returnValue = instance.GetPictureByPictureId(pictureId, _
    settings)
```

``` csharp
RetailImage GetPictureByPictureId(
    int pictureId,
    QueryResultSettings settings
)
```

``` c++
RetailImage^ GetPictureByPictureId(
    int pictureId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - pictureId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage](retailimage-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

