---
title: DataProtectionServiceRequestBase.Algorithm Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Algorithm Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase.Algorithm
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.dataprotectionservicerequestbase.algorithm(v=AX.60)
ms:contentKeyID: 65319961
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase.Algorithm
dev_langs:
- CSharp
- C++
- VB
---

# Algorithm Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Algorithm As String
    Get
    Private Set
'Usage
Dim instance As DataProtectionServiceRequestBase
Dim value As String

value = instance.Algorithm
```

``` csharp
[DataMemberAttribute]
public string Algorithm { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Algorithm {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataProtectionServiceRequestBase Class](dataprotectionservicerequestbase-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

