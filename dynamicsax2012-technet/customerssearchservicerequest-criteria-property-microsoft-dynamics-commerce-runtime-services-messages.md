---
title: CustomersSearchServiceRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.customerssearchservicerequest.criteria(v=AX.60)
ms:contentKeyID: 62215087
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets or sets the criteria to search for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Criteria As CustomerSearchCriteria
    Get
    Set
'Usage
Dim instance As CustomersSearchServiceRequest
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

[CustomersSearchServiceRequest Class](customerssearchservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

