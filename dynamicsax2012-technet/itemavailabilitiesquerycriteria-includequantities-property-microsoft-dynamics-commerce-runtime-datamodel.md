---
title: ItemAvailabilitiesQueryCriteria.IncludeQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncludeQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.IncludeQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.includequantities(v=AX.60)
ms:contentKeyID: 65321083
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.IncludeQuantities
dev_langs:
- CSharp
- C++
- VB
---

# IncludeQuantities Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether quantities required in the response.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncludeQuantities As Boolean
    Get
    Private Set
'Usage
Dim instance As ItemAvailabilitiesQueryCriteria
Dim value As Boolean

value = instance.IncludeQuantities
```

``` csharp
[DataMemberAttribute]
public bool IncludeQuantities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IncludeQuantities {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

