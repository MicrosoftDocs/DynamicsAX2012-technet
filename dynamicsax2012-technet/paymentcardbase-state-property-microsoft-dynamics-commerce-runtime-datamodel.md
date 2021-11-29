---
title: PaymentCardBase.State Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: State Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.State
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.state(v=AX.60)
ms:contentKeyID: 65321063
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.State
dev_langs:
- CSharp
- C++
- VB
---

# State Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for State.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property State As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.State

instance.State = value
```

``` csharp
[DataMemberAttribute]
public string State { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ State {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The state.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

