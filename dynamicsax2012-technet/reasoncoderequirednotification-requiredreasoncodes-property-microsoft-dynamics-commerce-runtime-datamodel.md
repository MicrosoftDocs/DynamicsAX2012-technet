---
title: ReasonCodeRequiredNotification.RequiredReasonCodes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequiredReasonCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification.RequiredReasonCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncoderequirednotification.requiredreasoncodes(v=AX.60)
ms:contentKeyID: 65322253
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification.RequiredReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# RequiredReasonCodes Property

Gets the required reason codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RequiredReasonCodes As IEnumerable(Of ReasonCode)
    Get
    Private Set
'Usage
Dim instance As ReasonCodeRequiredNotification
Dim value As IEnumerable(Of ReasonCode)

value = instance.RequiredReasonCodes
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ReasonCode> RequiredReasonCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ReasonCode^>^ RequiredReasonCodes {
    IEnumerable<ReasonCode^>^ get ();
    private: void set (IEnumerable<ReasonCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ReasonCodeRequiredNotification Class](reasoncoderequirednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

