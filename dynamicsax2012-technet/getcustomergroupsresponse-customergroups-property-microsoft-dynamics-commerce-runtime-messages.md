---
title: GetCustomerGroupsResponse.CustomerGroups Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CustomerGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsResponse.CustomerGroups
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getcustomergroupsresponse.customergroups(v=AX.60)
ms:contentKeyID: 62213576
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerGroupsResponse.CustomerGroups
dev_langs:
- CSharp
- C++
- VB
---

# CustomerGroups Property

Gets the channel customerGroups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerGroups As ReadOnlyCollection(Of CustomerGroup)
    Get
    Private Set
'Usage
Dim instance As GetCustomerGroupsResponse
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CustomerGroup](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCustomerGroupsResponse Class](getcustomergroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

