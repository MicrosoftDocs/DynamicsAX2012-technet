---
title: GetDiscountLinesDataRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountLinesDataRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdiscountlinesdatarequest.criteria(v=AX.60)
ms:contentKeyID: 65317726
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountLinesDataRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets query criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Criteria As DiscountLinesQueryCriteria
    Get
    Private Set
'Usage
Dim instance As GetDiscountLinesDataRequest
Dim value As DiscountLinesQueryCriteria

value = instance.Criteria
```

``` csharp
public DiscountLinesQueryCriteria Criteria { get; private set; }
```

``` c++
public:
property DiscountLinesQueryCriteria^ Criteria {
    DiscountLinesQueryCriteria^ get ();
    private: void set (DiscountLinesQueryCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLinesQueryCriteria](discountlinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DiscountLinesQueryCriteria](discountlinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetDiscountLinesDataRequest Class](getdiscountlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

