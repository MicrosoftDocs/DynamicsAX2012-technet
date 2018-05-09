---
title: IEODV1.OpenShift Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: OpenShift Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.OpenShift(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStaging@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ieodv1.openshift(v=AX.60)
ms:contentKeyID: 47343909
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.OpenShift
dev_langs:
- CSharp
- C++
- VB
---

# OpenShift Method

Opens a shift.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function OpenShift ( _
    ByRef shift As IPosBatchStaging _
) As Boolean
'Usage
Dim instance As IEODV1
Dim shift As IPosBatchStaging
Dim returnValue As Boolean

returnValue = instance.OpenShift(shift)
```

``` csharp
bool OpenShift(
    ref IPosBatchStaging shift
)
```

``` c++
bool OpenShift(
    IPosBatchStaging^% shift
)
```

#### Parameters

  - shift  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStaging](iposbatchstaging-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
false if user canceled the operation; otherwise, true.  

## See Also

#### Reference

[IEODV1 Interface](ieodv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

