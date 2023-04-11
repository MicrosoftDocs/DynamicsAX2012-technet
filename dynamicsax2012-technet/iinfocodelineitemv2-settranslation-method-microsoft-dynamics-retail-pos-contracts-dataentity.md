---
title: IInfoCodeLineItemV2.SetTranslation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SetTranslation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV2.SetTranslation(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv2.settranslation(v=AX.60)
ms:contentKeyID: 62205582
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV2.SetTranslation
dev_langs:
- CSharp
- C++
- VB
---

# SetTranslation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetTranslation ( _
    languageId As String, _
    infocodeTranslation As IInfocodeLineItemTranslation _
)
'Usage
Dim instance As IInfoCodeLineItemV2
Dim languageId As String
Dim infocodeTranslation As IInfocodeLineItemTranslation

instance.SetTranslation(languageId, infocodeTranslation)
```

``` csharp
void SetTranslation(
    string languageId,
    IInfocodeLineItemTranslation infocodeTranslation
)
```

``` c++
void SetTranslation(
    String^ languageId, 
    IInfocodeLineItemTranslation^ infocodeTranslation
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - infocodeTranslation  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation](iinfocodelineitemtranslation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IInfoCodeLineItemV2 Interface](iinfocodelineitemv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

