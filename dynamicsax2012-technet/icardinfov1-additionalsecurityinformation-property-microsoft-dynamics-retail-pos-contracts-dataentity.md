---
title: ICardInfoV1.AdditionalSecurityInformation Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AdditionalSecurityInformation Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.AdditionalSecurityInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.additionalsecurityinformation(v=AX.60)
ms:contentKeyID: 47129025
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.AdditionalSecurityInformation
dev_langs:
- CSharp
- C++
- VB
---

# AdditionalSecurityInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Additional card security information collected from a hardware device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AdditionalSecurityInformation As String
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String

value = instance.AdditionalSecurityInformation

instance.AdditionalSecurityInformation = value
```

``` csharp
string AdditionalSecurityInformation { get; set; }
```

``` c++
property String^ AdditionalSecurityInformation {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

