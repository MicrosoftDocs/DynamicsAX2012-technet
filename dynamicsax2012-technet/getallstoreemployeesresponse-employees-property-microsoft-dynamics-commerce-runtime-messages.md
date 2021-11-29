---
title: GetAllStoreEmployeesResponse.Employees Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Employees Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesResponse.Employees
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getallstoreemployeesresponse.employees(v=AX.60)
ms:contentKeyID: 62202828
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesResponse.Employees
dev_langs:
- CSharp
- C++
- VB
---

# Employees Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of employees.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Employees As ReadOnlyCollection(Of Employee)
    Get
    Private Set
'Usage
Dim instance As GetAllStoreEmployeesResponse
Dim value As ReadOnlyCollection(Of Employee)

value = instance.Employees
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Employee> Employees { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Employee^>^ Employees {
    ReadOnlyCollection<Employee^>^ get ();
    private: void set (ReadOnlyCollection<Employee^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAllStoreEmployeesResponse Class](getallstoreemployeesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

