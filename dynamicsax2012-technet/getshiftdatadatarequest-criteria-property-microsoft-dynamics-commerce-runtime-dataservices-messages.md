---
title: GetShiftDataDataRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataDataRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshiftdatadatarequest.criteria(v=AX.60)
ms:contentKeyID: 65316786
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataDataRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the query criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Criteria As ShiftDataQueryCriteria
    Get
    Private Set
'Usage
Dim instance As GetShiftDataDataRequest
Dim value As ShiftDataQueryCriteria

value = instance.Criteria
```

``` csharp
[DataMemberAttribute]
public ShiftDataQueryCriteria Criteria { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ShiftDataQueryCriteria^ Criteria {
    ShiftDataQueryCriteria^ get ();
    private: void set (ShiftDataQueryCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ShiftDataQueryCriteria](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetShiftDataDataRequest Class](getshiftdatadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

