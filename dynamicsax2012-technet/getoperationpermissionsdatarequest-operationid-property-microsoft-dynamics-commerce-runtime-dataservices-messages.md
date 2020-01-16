---
title: GetOperationPermissionsDataRequest.OperationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: OperationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest.OperationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getoperationpermissionsdatarequest.operationid(v=AX.60)
ms:contentKeyID: 65322881
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest.OperationId
dev_langs:
- CSharp
- C++
- VB
---

# OperationId Property

Gets the operation identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OperationId As RetailOperation
    Get
    Private Set
'Usage
Dim instance As GetOperationPermissionsDataRequest
Dim value As RetailOperation

value = instance.OperationId
```

``` csharp
[DataMemberAttribute]
public RetailOperation OperationId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property RetailOperation OperationId {
    RetailOperation get ();
    private: void set (RetailOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The operation identifier.  

## See Also

#### Reference

[GetOperationPermissionsDataRequest Class](getoperationpermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

