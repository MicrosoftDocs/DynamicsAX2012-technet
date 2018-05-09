---
title: IChannelDataManager.GetChannelTenderTypes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelTenderTypes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelTenderTypes(System.Int64,System.Nullable{System.Int32},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchanneltendertypes(v=AX.60)
ms:contentKeyID: 65322452
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelTenderTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelTenderTypes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelTenderTypes ( _
    channelId As Long, _
    countingRequired As Nullable(Of Integer), _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of TenderType)
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim countingRequired As Nullable(Of Integer)
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of TenderType)

returnValue = instance.GetChannelTenderTypes(channelId, _
    countingRequired, settings)
```

``` csharp
ReadOnlyCollection<TenderType> GetChannelTenderTypes(
    long channelId,
    Nullable<int> countingRequired,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<TenderType^>^ GetChannelTenderTypes(
    long long channelId, 
    Nullable<int> countingRequired, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - countingRequired  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

