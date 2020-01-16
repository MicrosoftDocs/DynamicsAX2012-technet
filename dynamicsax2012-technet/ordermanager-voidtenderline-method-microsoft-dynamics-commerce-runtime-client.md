---
title: OrderManager.VoidTenderLine Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: VoidTenderLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.VoidTenderLine(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.voidtenderline(v=AX.60)
ms:contentKeyID: 65322003
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.VoidTenderLine
dev_langs:
- CSharp
- C++
- VB
---

# VoidTenderLine Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function VoidTenderLine ( _
    cartId As String, _
    tenderLineId As String, _
    reasonCodeLines As IEnumerable(Of ReasonCodeLine), _
    isPreprocessed As Boolean _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim tenderLineId As String
Dim reasonCodeLines As IEnumerable(Of ReasonCodeLine)
Dim isPreprocessed As Boolean
Dim returnValue As Cart

returnValue = instance.VoidTenderLine(cartId, _
    tenderLineId, reasonCodeLines, isPreprocessed)
```

``` csharp
public Cart VoidTenderLine(
    string cartId,
    string tenderLineId,
    IEnumerable<ReasonCodeLine> reasonCodeLines,
    bool isPreprocessed
)
```

``` c++
public:
Cart^ VoidTenderLine(
    String^ cartId, 
    String^ tenderLineId, 
    IEnumerable<ReasonCodeLine^>^ reasonCodeLines, 
    bool isPreprocessed
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderLineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonCodeLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - isPreprocessed  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

