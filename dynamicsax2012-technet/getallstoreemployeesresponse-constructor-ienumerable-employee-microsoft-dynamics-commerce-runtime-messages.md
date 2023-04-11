---
title: GetAllStoreEmployeesResponse Constructor (IEnumerable(Employee)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAllStoreEmployeesResponse Constructor (IEnumerable(Employee))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllStoreEmployeesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getallstoreemployeesresponse.getallstoreemployeesresponse(v=AX.60)
ms:contentKeyID: 62206559
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAllStoreEmployeesResponse Constructor (IEnumerable(Employee))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAllStoreEmployeesResponse](getallstoreemployeesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    employees As IEnumerable(Of Employee) _
)
'Usage
Dim employees As IEnumerable(Of Employee)

Dim instance As New GetAllStoreEmployeesResponse(employees)
```

``` csharp
public GetAllStoreEmployeesResponse(
    IEnumerable<Employee> employees
)
```

``` c++
public:
GetAllStoreEmployeesResponse(
    IEnumerable<Employee^>^ employees
)
```

#### Parameters

  - employees  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAllStoreEmployeesResponse Class](getallstoreemployeesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAllStoreEmployeesResponse Overload](getallstoreemployeesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

