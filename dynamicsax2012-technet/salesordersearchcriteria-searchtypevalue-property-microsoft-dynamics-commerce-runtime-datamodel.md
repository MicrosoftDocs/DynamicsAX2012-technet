---
title: SalesOrderSearchCriteria.SearchTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.searchtypevalue(v=AX.60)
ms:contentKeyID: 65319524
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# SearchTypeValue Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchTypeValue As Integer
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As Integer

value = instance.SearchTypeValue

instance.SearchTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int SearchTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int SearchTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

