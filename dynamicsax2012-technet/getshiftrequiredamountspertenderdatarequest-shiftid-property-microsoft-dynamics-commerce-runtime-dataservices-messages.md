---
title: GetShiftRequiredAmountsPerTenderDataRequest.ShiftId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ShiftId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftRequiredAmountsPerTenderDataRequest.ShiftId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshiftrequiredamountspertenderdatarequest.shiftid(v=AX.60)
ms:contentKeyID: 65317137
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftRequiredAmountsPerTenderDataRequest.ShiftId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftId Property

Gets or sets the shift identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftId As String
    Get
    Set
'Usage
Dim instance As GetShiftRequiredAmountsPerTenderDataRequest
Dim value As String

value = instance.ShiftId

instance.ShiftId = value
```

``` csharp
[DataMemberAttribute]
public string ShiftId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShiftId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetShiftRequiredAmountsPerTenderDataRequest Class](getshiftrequiredamountspertenderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

