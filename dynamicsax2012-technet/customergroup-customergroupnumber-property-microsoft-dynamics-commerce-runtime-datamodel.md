---
title: CustomerGroup.CustomerGroupNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerGroupNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerGroup.CustomerGroupNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customergroup.customergroupnumber(v=AX.60)
ms:contentKeyID: 62202832
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerGroup.CustomerGroupNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerGroupNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CUSTGROUP")> _
Public Property CustomerGroupNumber As String
    Get
    Set
'Usage
Dim instance As CustomerGroup
Dim value As String

value = instance.CustomerGroupNumber

instance.CustomerGroupNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CUSTGROUP")]
public string CustomerGroupNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CUSTGROUP")]
public:
property String^ CustomerGroupNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomerGroup Class](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

