---
title: IBusinessLogicV1.CustomerSystem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CustomerSystem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.CustomerSystem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.ibusinesslogicv1.customersystem(v=AX.60)
ms:contentKeyID: 47128833
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogicV1.CustomerSystem
dev_langs:
- CSharp
- C++
- VB
---

# CustomerSystem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CustomerSystem As ICustomerSystem
    Get
'Usage
Dim instance As IBusinessLogicV1
Dim value As ICustomerSystem

value = instance.CustomerSystem
```

``` csharp
ICustomerSystem CustomerSystem { get; }
```

``` c++
property ICustomerSystem^ CustomerSystem {
    ICustomerSystem^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystem](icustomersystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)  
Returns [ICustomerSystem](icustomersystem-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md).  

## See Also

#### Reference

[IBusinessLogicV1 Interface](ibusinesslogicv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

