---
title: IPinPadInfoV1.Status Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPinPadInfoV1.Status
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipinpadinfov1.status(v=AX.60)
ms:contentKeyID: 47129029
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPinPadInfoV1.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property

Gets or sets the pin entry status.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Status As PinPadEntryStatus
    Get
    Set
'Usage
Dim instance As IPinPadInfoV1
Dim value As PinPadEntryStatus

value = instance.Status

instance.Status = value
```

``` csharp
PinPadEntryStatus Status { get; set; }
```

``` c++
property PinPadEntryStatus Status {
    PinPadEntryStatus get ();
    void set (PinPadEntryStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus](pinpadentrystatus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryStatus](pinpadentrystatus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[IPinPadInfoV1 Interface](ipinpadinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

