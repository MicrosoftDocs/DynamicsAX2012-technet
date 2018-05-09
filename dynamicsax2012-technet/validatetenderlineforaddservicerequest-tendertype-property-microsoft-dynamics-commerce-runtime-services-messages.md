---
title: ValidateTenderLineForAddServiceRequest.TenderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateTenderLineForAddServiceRequest.TenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.validatetenderlineforaddservicerequest.tendertype(v=AX.60)
ms:contentKeyID: 65320057
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateTenderLineForAddServiceRequest.TenderType
dev_langs:
- CSharp
- C++
- VB
---

# TenderType Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderType As TenderType
    Get
    Set
'Usage
Dim instance As ValidateTenderLineForAddServiceRequest
Dim value As TenderType

value = instance.TenderType

instance.TenderType = value
```

``` csharp
[DataMemberAttribute]
public TenderType TenderType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TenderType^ TenderType {
    TenderType^ get ();
    void set (TenderType^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ValidateTenderLineForAddServiceRequest Class](validatetenderlineforaddservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

