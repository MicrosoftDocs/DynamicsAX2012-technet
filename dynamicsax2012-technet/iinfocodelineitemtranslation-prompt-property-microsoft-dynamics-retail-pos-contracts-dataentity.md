---
title: IInfocodeLineItemTranslation.Prompt Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Prompt Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation.Prompt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemtranslation.prompt(v=AX.60)
ms:contentKeyID: 62202316
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation.Prompt
dev_langs:
- CSharp
- C++
- VB
---

# Prompt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The text that is prompted when the user is prompted for the input of the infocode information.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Prompt As String
    Get
    Set
'Usage
Dim instance As IInfocodeLineItemTranslation
Dim value As String

value = instance.Prompt

instance.Prompt = value
```

``` csharp
string Prompt { get; set; }
```

``` c++
property String^ Prompt {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IInfocodeLineItemTranslation Interface](iinfocodelineitemtranslation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

