---
title: QueryResultSettings.Sorting Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Sorting Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.Sorting
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.sorting(v=AX.60)
ms:contentKeyID: 65316079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.Sorting
dev_langs:
- CSharp
- C++
- VB
---

# Sorting Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sorting information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Sorting As SortingInfo
    Get
    Set
'Usage
Dim instance As QueryResultSettings
Dim value As SortingInfo

value = instance.Sorting

instance.Sorting = value
```

``` csharp
[DataMemberAttribute]
public SortingInfo Sorting { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SortingInfo^ Sorting {
    SortingInfo^ get ();
    void set (SortingInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

