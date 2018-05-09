---
title: ICCTVV1.CCTVErrorOutput Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CCTVErrorOutput Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICCTVV1.CCTVErrorOutput(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icctvv1.cctverroroutput(v=AX.60)
ms:contentKeyID: 47344197
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICCTVV1.CCTVErrorOutput
dev_langs:
- CSharp
- C++
- VB
---

# CCTVErrorOutput Method

Sends the current error message in Retail POS to the CCTV.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CCTVErrorOutput ( _
    text As String _
)
'Usage
Dim instance As ICCTVV1
Dim text As String

instance.CCTVErrorOutput(text)
```

``` csharp
void CCTVErrorOutput(
    string text
)
```

``` c++
void CCTVErrorOutput(
    String^ text
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICCTVV1 Interface](icctvv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

