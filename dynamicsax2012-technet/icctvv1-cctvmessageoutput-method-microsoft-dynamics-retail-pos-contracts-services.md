---
title: ICCTVV1.CCTVMessageOutput Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CCTVMessageOutput Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICCTVV1.CCTVMessageOutput(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icctvv1.cctvmessageoutput(v=AX.60)
ms:contentKeyID: 47344360
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICCTVV1.CCTVMessageOutput
dev_langs:
- CSharp
- C++
- VB
---

# CCTVMessageOutput Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sends the current message in Retail POS to the CCTV.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CCTVMessageOutput ( _
    text As String _
)
'Usage
Dim instance As ICCTVV1
Dim text As String

instance.CCTVMessageOutput(text)
```

``` csharp
void CCTVMessageOutput(
    string text
)
```

``` c++
void CCTVMessageOutput(
    String^ text
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICCTVV1 Interface](icctvv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

