---
title: ITimeRegistrationV1.TimeRegistrations Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TimeRegistrations Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITimeRegistrationV1.TimeRegistrations(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.itimeregistrationv1.timeregistrations(v=AX.60)
ms:contentKeyID: 49830242
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITimeRegistrationV1.TimeRegistrations
dev_langs:
- CSharp
- C++
- VB
---

# TimeRegistrations Method

Time registration, this allows operator to register time clock in\\clock out time.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub TimeRegistrations ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ITimeRegistrationV1
Dim posTransaction As IPosTransaction

instance.TimeRegistrations(posTransaction)
```

``` csharp
void TimeRegistrations(
    IPosTransaction posTransaction
)
```

``` c++
void TimeRegistrations(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITimeRegistrationV1 Interface](itimeregistrationv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

