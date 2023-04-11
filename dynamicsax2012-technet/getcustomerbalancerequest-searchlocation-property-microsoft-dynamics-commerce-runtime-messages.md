---
title: GetCustomerBalanceRequest.SearchLocation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SearchLocation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceRequest.SearchLocation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomerbalancerequest.searchlocation(v=AX.60)
ms:contentKeyID: 65321415
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceRequest.SearchLocation
dev_langs:
- CSharp
- C++
- VB
---

# SearchLocation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchLocation As SearchLocation
    Get
    Set
'Usage
Dim instance As GetCustomerBalanceRequest
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

[GetCustomerBalanceRequest Class](getcustomerbalancerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

