---
title: CustomersSearchRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CustomersSearchRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.customerssearchrequest.criteria(v=AX.60)
ms:contentKeyID: 62215004
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CustomersSearchRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets or sets the criteria to search for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Criteria As CustomerSearchCriteria
    Get
    Set
'Usage
Dim instance As CustomersSearchRequest
Dim value As CustomerSearchCriteria

value = instance.Criteria

instance.Criteria = value
```

``` csharp
[DataMemberAttribute]
public CustomerSearchCriteria Criteria { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CustomerSearchCriteria^ Criteria {
    CustomerSearchCriteria^ get ();
    void set (CustomerSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria](customersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CustomerSearchCriteria](customersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CustomersSearchRequest Class](customerssearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

