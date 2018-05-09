---
title: SaveDropAndDeclareServiceRequest.TenderDropAndDeclareType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderDropAndDeclareType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest.TenderDropAndDeclareType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.savedropanddeclareservicerequest.tenderdropanddeclaretype(v=AX.60)
ms:contentKeyID: 62211140
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveDropAndDeclareServiceRequest.TenderDropAndDeclareType
dev_langs:
- CSharp
- C++
- VB
---

# TenderDropAndDeclareType Property

Gets or sets the tender drop and declare type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderDropAndDeclareType As TenderDropAndDeclareType
    Get
    Set
'Usage
Dim instance As SaveDropAndDeclareServiceRequest
Dim value As TenderDropAndDeclareType

value = instance.TenderDropAndDeclareType

instance.TenderDropAndDeclareType = value
```

``` csharp
[DataMemberAttribute]
public TenderDropAndDeclareType TenderDropAndDeclareType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TenderDropAndDeclareType TenderDropAndDeclareType {
    TenderDropAndDeclareType get ();
    void set (TenderDropAndDeclareType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDropAndDeclareType](tenderdropanddeclaretype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TenderDropAndDeclareType](tenderdropanddeclaretype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveDropAndDeclareServiceRequest Class](savedropanddeclareservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

