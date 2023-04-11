---
title: SalesOrderSearchCriteria.IncludeDetails Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncludeDetails Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.IncludeDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.includedetails(v=AX.60)
ms:contentKeyID: 62212384
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.IncludeDetails
dev_langs:
- CSharp
- C++
- VB
---

# IncludeDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to include order details (line information, order attributes etc).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncludeDetails As Boolean
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As Boolean

value = instance.IncludeDetails

instance.IncludeDetails = value
```

``` csharp
[DataMemberAttribute]
public bool IncludeDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IncludeDetails {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

