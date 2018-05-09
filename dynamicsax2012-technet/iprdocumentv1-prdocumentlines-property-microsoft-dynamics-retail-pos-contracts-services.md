---
title: IPRDocumentV1.PRDocumentLines Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PRDocumentLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocumentV1.PRDocumentLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iprdocumentv1.prdocumentlines(v=AX.60)
ms:contentKeyID: 47344459
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPRDocumentV1.PRDocumentLines
dev_langs:
- CSharp
- C++
- VB
---

# PRDocumentLines Property

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PRDocumentLines As IList(Of IPRDocumentLine)
    Get
    Set
'Usage
Dim instance As IPRDocumentV1
Dim value As IList(Of IPRDocumentLine)

value = instance.PRDocumentLines

instance.PRDocumentLines = value
```

``` csharp
IList<IPRDocumentLine> PRDocumentLines { get; set; }
```

``` c++
property IList<IPRDocumentLine^>^ PRDocumentLines {
    IList<IPRDocumentLine^>^ get ();
    void set (IList<IPRDocumentLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[IPRDocumentLine](iprdocumentline-interface-microsoft-dynamics-retail-pos-contracts-services.md)\>  
The [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)) list.  

## See Also

#### Reference

[IPRDocumentV1 Interface](iprdocumentv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

