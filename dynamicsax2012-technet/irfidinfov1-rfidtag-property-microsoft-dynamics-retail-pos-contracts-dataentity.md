---
title: IRFIDInfoV1.RFIDTag Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RFIDTag Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfoV1.RFIDTag
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.irfidinfov1.rfidtag(v=AX.60)
ms:contentKeyID: 47128955
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfoV1.RFIDTag
dev_langs:
- CSharp
- C++
- VB
---

# RFIDTag Property

The RFID tag that was read from the RFID scanner.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RFIDTag As String
    Get
    Set
'Usage
Dim instance As IRFIDInfoV1
Dim value As String

value = instance.RFIDTag

instance.RFIDTag = value
```

``` csharp
string RFIDTag { get; set; }
```

``` c++
property String^ RFIDTag {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IRFIDInfoV1 Interface](irfidinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

