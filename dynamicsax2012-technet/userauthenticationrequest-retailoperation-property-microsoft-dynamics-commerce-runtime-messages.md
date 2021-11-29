---
title: UserAuthenticationRequest.RetailOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RetailOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.RetailOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrequest.retailoperation(v=AX.60)
ms:contentKeyID: 62210791
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.RetailOperation
dev_langs:
- CSharp
- C++
- VB
---

# RetailOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the retail operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetailOperation As RetailOperation
    Get
    Set
'Usage
Dim instance As UserAuthenticationRequest
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
Retail Operation.  

## See Also

#### Reference

[UserAuthenticationRequest Class](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

