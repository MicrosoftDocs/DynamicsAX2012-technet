---
title: UnableToRetrieveStoresNotification.Area Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Area Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToRetrieveStoresNotification.Area
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletoretrievestoresnotification.area(v=AX.60)
ms:contentKeyID: 65320907
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToRetrieveStoresNotification.Area
dev_langs:
- CSharp
- C++
- VB
---

# Area Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the search area.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Area As SearchArea
    Get
    Private Set
'Usage
Dim instance As UnableToRetrieveStoresNotification
Dim value As SearchArea

value = instance.Area
```

``` csharp
[DataMemberAttribute]
public SearchArea Area { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SearchArea^ Area {
    SearchArea^ get ();
    private: void set (SearchArea^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UnableToRetrieveStoresNotification Class](unabletoretrievestoresnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

