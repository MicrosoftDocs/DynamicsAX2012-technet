---
title: EntityDataServiceRequest(TRequestEntity, TResponseEntity).RequestParameter Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: RequestParameter Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest`2.RequestParameter
ms:mtpsurl: https://technet.microsoft.com/library/Dn968419(v=AX.60)
ms:contentKeyID: 65321035
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest`2.RequestParameter
dev_langs:
- CSharp
- C++
- VB
---

# RequestParameter Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the request object for entity data service.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RequestParameter As TRequestEntity
    Get
    Private Set
'Usage
Dim instance As EntityDataServiceRequest
Dim value As TRequestEntity

value = instance.RequestParameter
```

``` csharp
[DataMemberAttribute]
public TRequestEntity RequestParameter { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TRequestEntity RequestParameter {
    TRequestEntity get ();
    private: void set (TRequestEntity value);
}
```

#### Property Value

Type: [TRequestEntity](entitydataservicerequest-trequestentity-tresponseentity-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
Returns \[{0}\].  

## See Also

#### Reference

[EntityDataServiceRequest\<TRequestEntity, TResponseEntity\> Class](entitydataservicerequest-trequestentity-tresponseentity-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

