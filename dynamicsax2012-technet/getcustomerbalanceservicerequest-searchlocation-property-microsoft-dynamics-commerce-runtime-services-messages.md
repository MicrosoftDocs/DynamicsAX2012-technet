---
title: GetCustomerBalanceServiceRequest.SearchLocation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SearchLocation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.SearchLocation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerbalanceservicerequest.searchlocation(v=AX.60)
ms:contentKeyID: 65319362
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.SearchLocation
dev_langs:
- CSharp
- C++
- VB
---

# SearchLocation Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchLocation As SearchLocation
    Get
    Set
'Usage
Dim instance As GetCustomerBalanceServiceRequest
Dim value As SearchLocation

value = instance.SearchLocation

instance.SearchLocation = value
```

``` csharp
[DataMemberAttribute]
public SearchLocation SearchLocation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SearchLocation SearchLocation {
    SearchLocation get ();
    void set (SearchLocation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation](searchlocation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCustomerBalanceServiceRequest Class](getcustomerbalanceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

