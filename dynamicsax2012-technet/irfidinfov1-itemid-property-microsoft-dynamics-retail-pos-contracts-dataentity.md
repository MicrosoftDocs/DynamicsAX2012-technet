---
title: IRFIDInfoV1.ItemId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfoV1.ItemId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.irfidinfov1.itemid(v=AX.60)
ms:contentKeyID: 47129205
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfoV1.ItemId
dev_langs:
- CSharp
- C++
- VB
---

# ItemId Property

The item ID found in the database that corresponds to the RFID tag that was scanned.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemId As String
    Get
    Set
'Usage
Dim instance As IRFIDInfoV1
Dim value As String

value = instance.ItemId

instance.ItemId = value
```

``` csharp
string ItemId { get; set; }
```

``` c++
property String^ ItemId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IRFIDInfoV1 Interface](irfidinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

