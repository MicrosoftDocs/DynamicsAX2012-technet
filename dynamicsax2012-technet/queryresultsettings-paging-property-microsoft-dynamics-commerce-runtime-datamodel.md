---
title: QueryResultSettings.Paging Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Paging Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.Paging
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.paging(v=AX.60)
ms:contentKeyID: 65322011
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.Paging
dev_langs:
- CSharp
- C++
- VB
---

# Paging Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the pagination information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Paging As PagingInfo
    Get
    Set
'Usage
Dim instance As QueryResultSettings
Dim value As PagingInfo

value = instance.Paging

instance.Paging = value
```

``` csharp
[DataMemberAttribute]
public PagingInfo Paging { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property PagingInfo^ Paging {
    PagingInfo^ get ();
    void set (PagingInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

