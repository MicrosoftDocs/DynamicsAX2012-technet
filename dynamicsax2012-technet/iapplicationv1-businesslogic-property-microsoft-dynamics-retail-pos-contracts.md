---
title: IApplicationV1.BusinessLogic Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: BusinessLogic Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.BusinessLogic
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.businesslogic(v=AX.60)
ms:contentKeyID: 47129222
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.BusinessLogic
dev_langs:
- CSharp
- C++
- VB
---

# BusinessLogic Property

Gets the application business logic.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property BusinessLogic As IBusinessLogic
    Get
'Usage
Dim instance As IApplicationV1
Dim value As IBusinessLogic

value = instance.BusinessLogic
```

``` csharp
IBusinessLogic BusinessLogic { get; }
```

``` c++
property IBusinessLogic^ BusinessLogic {
    IBusinessLogic^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogic](ibusinesslogic-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IBusinessLogic](ibusinesslogic-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md) value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

