---
title: IInfoCodeLineItemV2.GetTranslation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GetTranslation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV2.GetTranslation(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv2.gettranslation(v=AX.60)
ms:contentKeyID: 62203511
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV2.GetTranslation
dev_langs:
- CSharp
- C++
- VB
---

# GetTranslation Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetTranslation ( _
    languageId As String _
) As IInfocodeLineItemTranslation
'Usage
Dim instance As IInfoCodeLineItemV2
Dim languageId As String
Dim returnValue As IInfocodeLineItemTranslation

returnValue = instance.GetTranslation(languageId)
```

``` csharp
IInfocodeLineItemTranslation GetTranslation(
    string languageId
)
```

``` c++
IInfocodeLineItemTranslation^ GetTranslation(
    String^ languageId
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation](iinfocodelineitemtranslation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IInfocodeLineItemTranslation](iinfocodelineitemtranslation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IInfoCodeLineItemV2 Interface](iinfocodelineitemv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

