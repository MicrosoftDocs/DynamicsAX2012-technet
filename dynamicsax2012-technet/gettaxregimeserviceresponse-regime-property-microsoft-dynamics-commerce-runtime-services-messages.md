---
title: GetTaxRegimeServiceResponse.Regime Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Regime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxRegimeServiceResponse.Regime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettaxregimeserviceresponse.regime(v=AX.60)
ms:contentKeyID: 62214498
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTaxRegimeServiceResponse.Regime
dev_langs:
- CSharp
- C++
- VB
---

# Regime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales tax regime information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Regime As String
    Get
    Private Set
'Usage
Dim instance As GetTaxRegimeServiceResponse
Dim value As String

value = instance.Regime
```

``` csharp
[DataMemberAttribute]
public string Regime { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Regime {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetTaxRegimeServiceResponse Class](gettaxregimeserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

