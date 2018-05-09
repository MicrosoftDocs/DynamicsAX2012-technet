---
title: GetCustomerGroupsServiceResponse Constructor (IEnumerable(CustomerGroup)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCustomerGroupsServiceResponse Constructor (IEnumerable(CustomerGroup))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerGroupsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerGroup})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomergroupsserviceresponse.getcustomergroupsserviceresponse(v=AX.60)
ms:contentKeyID: 62214170
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomerGroupsServiceResponse Constructor (IEnumerable(CustomerGroup))

Initializes a new instance of the [GetCustomerGroupsServiceResponse](getcustomergroupsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customerGroups As IEnumerable(Of CustomerGroup) _
)
'Usage
Dim customerGroups As IEnumerable(Of CustomerGroup)

Dim instance As New GetCustomerGroupsServiceResponse(customerGroups)
```

``` csharp
public GetCustomerGroupsServiceResponse(
    IEnumerable<CustomerGroup> customerGroups
)
```

``` c++
public:
GetCustomerGroupsServiceResponse(
    IEnumerable<CustomerGroup^>^ customerGroups
)
```

#### Parameters

  - customerGroups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CustomerGroup](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCustomerGroupsServiceResponse Class](getcustomergroupsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCustomerGroupsServiceResponse Overload](getcustomergroupsserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

