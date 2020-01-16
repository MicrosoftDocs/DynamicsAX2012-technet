---
title: GetOrdersRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getordersrequest.criteria(v=AX.60)
ms:contentKeyID: 62214733
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets the criteria to search for.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Criteria As SalesOrderSearchCriteria
    Get
    Private Set
'Usage
Dim instance As GetOrdersRequest
Dim value As SalesOrderSearchCriteria

value = instance.Criteria
```

``` csharp
[DataMemberAttribute]
public SalesOrderSearchCriteria Criteria { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrderSearchCriteria^ Criteria {
    SalesOrderSearchCriteria^ get ();
    private: void set (SalesOrderSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetOrdersRequest Class](getordersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

