---
title: SalesOrderSearchCriteria.SerialNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SerialNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SerialNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.serialnumber(v=AX.60)
ms:contentKeyID: 62208261
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SerialNumber
dev_langs:
- CSharp
- C++
- VB
---

# SerialNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item serial number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SerialNumber As String
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As String

value = instance.SerialNumber

instance.SerialNumber = value
```

``` csharp
[DataMemberAttribute]
public string SerialNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SerialNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

