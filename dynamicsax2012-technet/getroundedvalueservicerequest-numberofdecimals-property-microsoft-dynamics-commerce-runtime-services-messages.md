---
title: GetRoundedValueServiceRequest.NumberOfDecimals Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NumberOfDecimals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedValueServiceRequest.NumberOfDecimals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedvalueservicerequest.numberofdecimals(v=AX.60)
ms:contentKeyID: 62206617
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedValueServiceRequest.NumberOfDecimals
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfDecimals Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of decimals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberOfDecimals As Integer
    Get
    Private Set
'Usage
Dim instance As GetRoundedValueServiceRequest
Dim value As Integer

value = instance.NumberOfDecimals
```

``` csharp
[DataMemberAttribute]
public int NumberOfDecimals { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int NumberOfDecimals {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundedValueServiceRequest Class](getroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

