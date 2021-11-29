---
title: ICustomer Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ICustomer Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomer(v=AX.60)
ms:contentKeyID: 47344244
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomer
dev_langs:
- CSharp
- C++
- VB
---

# ICustomer Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomer interface is used for customer control: customer database search, customer changes, adding or deleting a customer instance.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("28169FFE-BEAF-4585-B8CE-F688F251402E")> _
Public Interface ICustomer _
    Inherits IService, ICustomerV1, ICustomerV2
'Usage
Dim instance As ICustomer
```

``` csharp
[GuidAttribute("28169FFE-BEAF-4585-B8CE-F688F251402E")]
public interface ICustomer : IService, 
    ICustomerV1, ICustomerV2
```

``` c++
[GuidAttribute(L"28169FFE-BEAF-4585-B8CE-F688F251402E")]
public interface class ICustomer : IService, 
    ICustomerV1, ICustomerV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

