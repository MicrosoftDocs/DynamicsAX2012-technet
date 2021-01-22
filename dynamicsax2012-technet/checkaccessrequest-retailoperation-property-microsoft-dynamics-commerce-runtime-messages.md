---
title: CheckAccessRequest.RetailOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RetailOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.RetailOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.checkaccessrequest.retailoperation(v=AX.60)
ms:contentKeyID: 62213066
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.RetailOperation
dev_langs:
- CSharp
- C++
- VB
---

# RetailOperation Property

Gets the operation permission.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetailOperation As RetailOperation
    Get
    Private Set
'Usage
Dim instance As CheckAccessRequest
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
The operation permission.  

## See Also

#### Reference

[CheckAccessRequest Class](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

