---
title: IUtilityV1.Translate Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: Translate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.Translate(Microsoft.Dynamics.Retail.Pos.Contracts.Services.EFTCardTypes)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.translate(v=AX.60)
ms:contentKeyID: 47129174
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.Translate
dev_langs:
- CSharp
- C++
- VB
---

# Translate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Helper method to translate EFTCardType enum value to a localized string

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Translate ( _
    eftCardType As EFTCardTypes _
) As String
'Usage
Dim instance As IUtilityV1
Dim eftCardType As EFTCardTypes
Dim returnValue As String

returnValue = instance.Translate(eftCardType)
```

``` csharp
string Translate(
    EFTCardTypes eftCardType
)
```

``` c++
String^ Translate(
    EFTCardTypes eftCardType
)
```

#### Parameters

  - eftCardType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.EFTCardTypes](eftcardtypes-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string representation of the EFT card type.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

