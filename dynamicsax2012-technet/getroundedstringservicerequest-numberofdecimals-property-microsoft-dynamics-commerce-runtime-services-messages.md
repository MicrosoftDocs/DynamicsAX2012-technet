---
title: GetRoundedStringServiceRequest.NumberOfDecimals Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NumberOfDecimals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.NumberOfDecimals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedstringservicerequest.numberofdecimals(v=AX.60)
ms:contentKeyID: 62208969
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.NumberOfDecimals
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
Dim instance As GetRoundedStringServiceRequest
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

[GetRoundedStringServiceRequest Class](getroundedstringservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

