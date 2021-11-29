---
title: UserLogOnServiceRequest.RetailOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RetailOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.RetailOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.retailoperation(v=AX.60)
ms:contentKeyID: 62207282
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.RetailOperation
dev_langs:
- CSharp
- C++
- VB
---

# RetailOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the retail operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetailOperation As RetailOperation
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceRequest
Dim value As RetailOperation

value = instance.RetailOperation
```

``` csharp
[DataMemberAttribute]
public RetailOperation RetailOperation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property RetailOperation RetailOperation {
    RetailOperation get ();
    private: void set (RetailOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

