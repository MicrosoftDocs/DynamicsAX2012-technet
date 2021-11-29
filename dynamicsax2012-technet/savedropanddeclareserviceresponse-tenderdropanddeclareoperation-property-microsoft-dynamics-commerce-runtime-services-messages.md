---
title: SaveDropAndDeclareServiceResponse.TenderDropAndDeclareOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderDropAndDeclareOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceResponse.TenderDropAndDeclareOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savedropanddeclareserviceresponse.tenderdropanddeclareoperation(v=AX.60)
ms:contentKeyID: 62202696
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceResponse.TenderDropAndDeclareOperation
dev_langs:
- CSharp
- C++
- VB
---

# TenderDropAndDeclareOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender drop and declare operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderDropAndDeclareOperation As DropAndDeclareTransaction
    Get
    Private Set
'Usage
Dim instance As SaveDropAndDeclareServiceResponse
Dim value As DropAndDeclareTransaction

value = instance.TenderDropAndDeclareOperation
```

``` csharp
[DataMemberAttribute]
public DropAndDeclareTransaction TenderDropAndDeclareOperation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DropAndDeclareTransaction^ TenderDropAndDeclareOperation {
    DropAndDeclareTransaction^ get ();
    private: void set (DropAndDeclareTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveDropAndDeclareServiceResponse Class](savedropanddeclareserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

