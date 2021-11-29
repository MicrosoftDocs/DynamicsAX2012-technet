---
title: IUtilityV1.CreateRFIDInfo Method (String, String) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateRFIDInfo Method (String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.CreateRFIDInfo(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.createrfidinfo(v=AX.60)
ms:contentKeyID: 47128806
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateRFIDInfo Method (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates an [IRFIDInfo](irfidinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateRFIDInfo ( _
    rfidTag As String, _
    itemId As String _
) As IRFIDInfo
'Usage
Dim instance As IUtilityV1
Dim rfidTag As String
Dim itemId As String
Dim returnValue As IRFIDInfo

returnValue = instance.CreateRFIDInfo(rfidTag, _
    itemId)
```

``` csharp
IRFIDInfo CreateRFIDInfo(
    string rfidTag,
    string itemId
)
```

``` c++
IRFIDInfo^ CreateRFIDInfo(
    String^ rfidTag, 
    String^ itemId
)
```

#### Parameters

  - rfidTag  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRFIDInfo](irfidinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The RFID info.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[CreateRFIDInfo Overload](iutilityv1-createrfidinfo-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

