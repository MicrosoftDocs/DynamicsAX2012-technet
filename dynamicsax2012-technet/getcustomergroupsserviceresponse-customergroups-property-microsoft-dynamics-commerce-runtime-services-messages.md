---
title: GetCustomerGroupsServiceResponse.CustomerGroups Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerGroupsServiceResponse.CustomerGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomergroupsserviceresponse.customergroups(v=AX.60)
ms:contentKeyID: 62205321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerGroupsServiceResponse.CustomerGroups
dev_langs:
- CSharp
- C++
- VB
---

# CustomerGroups Property

Gets the collection of customer group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerGroups As ReadOnlyCollection(Of CustomerGroup)
    Get
    Private Set
'Usage
Dim instance As GetCustomerGroupsServiceResponse
Dim value As ReadOnlyCollection(Of CustomerGroup)

value = instance.CustomerGroups
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CustomerGroup> CustomerGroups { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CustomerGroup^>^ CustomerGroups {
    ReadOnlyCollection<CustomerGroup^>^ get ();
    private: void set (ReadOnlyCollection<CustomerGroup^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CustomerGroup](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCustomerGroupsServiceResponse Class](getcustomergroupsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

