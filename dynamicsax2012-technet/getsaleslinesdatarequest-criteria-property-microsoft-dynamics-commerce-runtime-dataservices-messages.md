---
title: GetSalesLinesDataRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesLinesDataRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getsaleslinesdatarequest.criteria(v=AX.60)
ms:contentKeyID: 65319908
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSalesLinesDataRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets query criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Criteria As SalesLinesQueryCriteria
    Get
    Private Set
'Usage
Dim instance As GetSalesLinesDataRequest
Dim value As SalesLinesQueryCriteria

value = instance.Criteria
```

``` csharp
public SalesLinesQueryCriteria Criteria { get; private set; }
```

``` c++
public:
property SalesLinesQueryCriteria^ Criteria {
    SalesLinesQueryCriteria^ get ();
    private: void set (SalesLinesQueryCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLinesQueryCriteria](saleslinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesLinesQueryCriteria](saleslinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetSalesLinesDataRequest Class](getsaleslinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

