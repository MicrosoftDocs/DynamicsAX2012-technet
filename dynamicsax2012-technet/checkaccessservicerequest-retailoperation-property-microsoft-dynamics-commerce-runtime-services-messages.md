---
title: CheckAccessServiceRequest.RetailOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RetailOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.RetailOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.retailoperation(v=AX.60)
ms:contentKeyID: 62204731
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.RetailOperation
dev_langs:
- CSharp
- C++
- VB
---

# RetailOperation Property

Gets or sets the Operation Permission.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetailOperation As RetailOperation
    Get
    Set
'Usage
Dim instance As CheckAccessServiceRequest
Dim value As RetailOperation

value = instance.RetailOperation

instance.RetailOperation = value
```

``` csharp
[DataMemberAttribute]
public RetailOperation RetailOperation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property RetailOperation RetailOperation {
    RetailOperation get ();
    void set (RetailOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Operation Name.  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

