---
title: GetReasonCodesResponse.ReasonCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReasonCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesResponse.ReasonCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreasoncodesresponse.reasoncodes(v=AX.60)
ms:contentKeyID: 62210585
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesResponse.ReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodes Property

Gets the reason codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodes As ReadOnlyCollection(Of ReasonCode)
    Get
    Private Set
'Usage
Dim instance As GetReasonCodesResponse
Dim value As ReadOnlyCollection(Of ReasonCode)

value = instance.ReasonCodes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ReasonCode> ReasonCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ReasonCode^>^ ReasonCodes {
    ReadOnlyCollection<ReasonCode^>^ get ();
    private: void set (ReadOnlyCollection<ReasonCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetReasonCodesResponse Class](getreasoncodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

