---
title: GetCustomerGroupsResponse Constructor (IEnumerable(CustomerGroup)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCustomerGroupsResponse Constructor (IEnumerable(CustomerGroup))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerGroup})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomergroupsresponse.getcustomergroupsresponse(v=AX.60)
ms:contentKeyID: 62203415
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomerGroupsResponse Constructor (IEnumerable(CustomerGroup))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCustomerGroupsResponse](getcustomergroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customerGroups As IEnumerable(Of CustomerGroup) _
)
'Usage
Dim customerGroups As IEnumerable(Of CustomerGroup)

Dim instance As New GetCustomerGroupsResponse(customerGroups)
```

``` csharp
public GetCustomerGroupsResponse(
    IEnumerable<CustomerGroup> customerGroups
)
```

``` c++
public:
GetCustomerGroupsResponse(
    IEnumerable<CustomerGroup^>^ customerGroups
)
```

#### Parameters

  - customerGroups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CustomerGroup](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCustomerGroupsResponse Class](getcustomergroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetCustomerGroupsResponse Overload](getcustomergroupsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

