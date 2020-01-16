---
title: SaveTenderLineRequest.PreprocessedTenderLine Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PreprocessedTenderLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.PreprocessedTenderLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savetenderlinerequest.preprocessedtenderline(v=AX.60)
ms:contentKeyID: 65320873
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.PreprocessedTenderLine
dev_langs:
- CSharp
- C++
- VB
---

# PreprocessedTenderLine Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PreprocessedTenderLine As TenderLine
    Get
    Set
'Usage
Dim instance As SaveTenderLineRequest
Dim value As TenderLine

value = instance.PreprocessedTenderLine

instance.PreprocessedTenderLine = value
```

``` csharp
[DataMemberAttribute]
public TenderLine PreprocessedTenderLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TenderLine^ PreprocessedTenderLine {
    TenderLine^ get ();
    void set (TenderLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveTenderLineRequest Class](savetenderlinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

