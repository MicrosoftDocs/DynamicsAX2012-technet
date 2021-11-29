---
title: LoyaltyManager.Locale Property  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Locale Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.Locale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.locale(v=AX.60)
ms:contentKeyID: 62204589
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.Locale
dev_langs:
- CSharp
- C++
- VB
---

# Locale Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the locale.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Property Locale As String
    Get
    Set
'Usage
Dim instance As LoyaltyManager
Dim value As String

value = instance.Locale

instance.Locale = value
```

``` csharp
public string Locale { get; set; }
```

``` c++
public:
property String^ Locale {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

