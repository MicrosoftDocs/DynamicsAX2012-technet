---
title: IScanInfoV1.RFIDFound Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RFIDFound Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.RFIDFound
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iscaninfov1.rfidfound(v=AX.60)
ms:contentKeyID: 47128990
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfoV1.RFIDFound
dev_langs:
- CSharp
- C++
- VB
---

# RFIDFound Property

Was the RFID scanned found in POS database?

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RFIDFound As RFIDType
    Get
    Set
'Usage
Dim instance As IScanInfoV1
Dim value As RFIDType

value = instance.RFIDFound

instance.RFIDFound = value
```

``` csharp
RFIDType RFIDFound { get; set; }
```

``` c++
property RFIDType RFIDFound {
    RFIDType get ();
    void set (RFIDType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDType](rfidtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDType](rfidtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[IScanInfoV1 Interface](iscaninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

