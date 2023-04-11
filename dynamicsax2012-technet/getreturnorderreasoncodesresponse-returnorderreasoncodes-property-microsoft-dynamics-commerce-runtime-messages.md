---
title: GetReturnOrderReasonCodesResponse.ReturnOrderReasonCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReturnOrderReasonCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReturnOrderReasonCodesResponse.ReturnOrderReasonCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreturnorderreasoncodesresponse.returnorderreasoncodes(v=AX.60)
ms:contentKeyID: 65323098
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReturnOrderReasonCodesResponse.ReturnOrderReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# ReturnOrderReasonCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnOrderReasonCodes As ReadOnlyCollection(Of ReasonCode)
    Get
    Private Set
'Usage
Dim instance As GetReturnOrderReasonCodesResponse
Dim value As ReadOnlyCollection(Of ReasonCode)

value = instance.ReturnOrderReasonCodes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ReasonCode> ReturnOrderReasonCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ReasonCode^>^ ReturnOrderReasonCodes {
    ReadOnlyCollection<ReasonCode^>^ get ();
    private: void set (ReadOnlyCollection<ReasonCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReturnOrderReasonCodesResponse Class](getreturnorderreasoncodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

