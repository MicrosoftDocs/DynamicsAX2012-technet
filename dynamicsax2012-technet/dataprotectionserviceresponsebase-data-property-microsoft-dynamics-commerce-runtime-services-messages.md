---
title: DataProtectionServiceResponseBase.Data Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Data Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DataProtectionServiceResponseBase.Data
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.dataprotectionserviceresponsebase.data(v=AX.60)
ms:contentKeyID: 65322723
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DataProtectionServiceResponseBase.Data
dev_langs:
- CSharp
- C++
- VB
---

# Data Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Data As String
    Get
    Private Set
'Usage
Dim instance As DataProtectionServiceResponseBase
Dim value As String

value = instance.Data
```

``` csharp
[DataMemberAttribute]
public string Data { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Data {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataProtectionServiceResponseBase Class](dataprotectionserviceresponsebase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

