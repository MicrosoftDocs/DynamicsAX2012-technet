---
title: EmployeeActivitySearchCriteria.EmployeeActivityTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeeActivityTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria.EmployeeActivityTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivitysearchcriteria.employeeactivitytypes(v=AX.60)
ms:contentKeyID: 62209983
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria.EmployeeActivityTypes
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivityTypes Property

Gets or sets the employee activity types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmployeeActivityTypes As IList(Of EmployeeActivityType)
    Get
    Set
'Usage
Dim instance As EmployeeActivitySearchCriteria
Dim value As IList(Of EmployeeActivityType)

value = instance.EmployeeActivityTypes

instance.EmployeeActivityTypes = value
```

``` csharp
[DataMemberAttribute]
public IList<EmployeeActivityType> EmployeeActivityTypes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<EmployeeActivityType>^ EmployeeActivityTypes {
    IList<EmployeeActivityType>^ get ();
    void set (IList<EmployeeActivityType>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeActivitySearchCriteria Class](employeeactivitysearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

