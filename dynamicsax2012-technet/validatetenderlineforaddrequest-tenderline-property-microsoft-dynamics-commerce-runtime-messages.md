---
title: ValidateTenderLineForAddRequest.TenderLine Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TenderLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateTenderLineForAddRequest.TenderLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.validatetenderlineforaddrequest.tenderline(v=AX.60)
ms:contentKeyID: 65319271
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateTenderLineForAddRequest.TenderLine
dev_langs:
- CSharp
- C++
- VB
---

# TenderLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property TenderLine As TenderLine
    Get
    Private Set
'Usage
Dim instance As ValidateTenderLineForAddRequest
Dim value As TenderLine

value = instance.TenderLine
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public TenderLine TenderLine { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property TenderLine^ TenderLine {
    TenderLine^ get ();
    private: void set (TenderLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ValidateTenderLineForAddRequest Class](validatetenderlineforaddrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

