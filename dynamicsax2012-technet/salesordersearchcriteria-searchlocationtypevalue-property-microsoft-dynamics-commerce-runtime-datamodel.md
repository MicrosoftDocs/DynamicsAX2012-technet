---
title: SalesOrderSearchCriteria.SearchLocationTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchLocationTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchLocationTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.searchlocationtypevalue(v=AX.60)
ms:contentKeyID: 62214952
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchLocationTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# SearchLocationTypeValue Property

Gets or sets the search location value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchLocationTypeValue As Integer
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As Integer

value = instance.SearchLocationTypeValue

instance.SearchLocationTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int SearchLocationTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int SearchLocationTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

