---
title: SaveVoidTransactionRequest.ReasonCodeLines Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReasonCodeLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveVoidTransactionRequest.ReasonCodeLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savevoidtransactionrequest.reasoncodelines(v=AX.60)
ms:contentKeyID: 62211910
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveVoidTransactionRequest.ReasonCodeLines
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeLines Property

Gets or sets the reason code lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeLines As IEnumerable(Of ReasonCodeLine)
    Get
    Set
'Usage
Dim instance As SaveVoidTransactionRequest
Dim value As IEnumerable(Of ReasonCodeLine)

value = instance.ReasonCodeLines

instance.ReasonCodeLines = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ReasonCodeLine> ReasonCodeLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ReasonCodeLine^>^ ReasonCodeLines {
    IEnumerable<ReasonCodeLine^>^ get ();
    void set (IEnumerable<ReasonCodeLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SaveVoidTransactionRequest Class](savevoidtransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

