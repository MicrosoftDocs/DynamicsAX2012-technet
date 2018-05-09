---
title: ILineDisplayV1.DisplayText Method (String, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DisplayText Method (String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILineDisplayV1.DisplayText(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ilinedisplayv1.displaytext(v=AX.60)
ms:contentKeyID: 47343878
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DisplayText Method (String, String)

Display two lines on the line display.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub DisplayText ( _
    line1Text As String, _
    line2Text As String _
)
'Usage
Dim instance As ILineDisplayV1
Dim line1Text As String
Dim line2Text As String

instance.DisplayText(line1Text, line2Text)
```

``` csharp
void DisplayText(
    string line1Text,
    string line2Text
)
```

``` c++
void DisplayText(
    String^ line1Text, 
    String^ line2Text
)
```

#### Parameters

  - line1Text  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - line2Text  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ILineDisplayV1 Interface](ilinedisplayv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[DisplayText Overload](ilinedisplayv1-displaytext-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

