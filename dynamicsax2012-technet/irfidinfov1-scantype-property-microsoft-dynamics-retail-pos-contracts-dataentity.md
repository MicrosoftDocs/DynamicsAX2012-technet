---
title: IRFIDInfoV1.ScanType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ScanType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfoV1.ScanType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.irfidinfov1.scantype(v=AX.60)
ms:contentKeyID: 47128977
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfoV1.ScanType
dev_langs:
- CSharp
- C++
- VB
---

# ScanType Property

Indicate whether the RFID tag was found in the database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ScanType As RFIDType
    Get
    Set
'Usage
Dim instance As IRFIDInfoV1
Dim value As RFIDType

value = instance.ScanType

instance.ScanType = value
```

``` csharp
RFIDType ScanType { get; set; }
```

``` c++
property RFIDType ScanType {
    RFIDType get ();
    void set (RFIDType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDType](rfidtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDType](rfidtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IRFIDInfoV1 Interface](irfidinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

