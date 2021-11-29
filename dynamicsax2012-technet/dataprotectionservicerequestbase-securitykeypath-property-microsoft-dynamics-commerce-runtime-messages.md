---
title: DataProtectionServiceRequestBase.SecurityKeyPath Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SecurityKeyPath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase.SecurityKeyPath
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.dataprotectionservicerequestbase.securitykeypath(v=AX.60)
ms:contentKeyID: 65318470
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase.SecurityKeyPath
dev_langs:
- CSharp
- C++
- VB
---

# SecurityKeyPath Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SecurityKeyPath As String
    Get
    Private Set
'Usage
Dim instance As DataProtectionServiceRequestBase
Dim value As String

value = instance.SecurityKeyPath
```

``` csharp
[DataMemberAttribute]
public string SecurityKeyPath { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SecurityKeyPath {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataProtectionServiceRequestBase Class](dataprotectionservicerequestbase-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

