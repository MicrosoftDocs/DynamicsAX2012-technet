---
title: DataProtectionServiceRequestBase.Data Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Data Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase.Data
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.dataprotectionservicerequestbase.data(v=AX.60)
ms:contentKeyID: 65318107
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DataProtectionServiceRequestBase.Data
dev_langs:
- CSharp
- C++
- VB
---

# Data Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Data As String
    Get
    Private Set
'Usage
Dim instance As DataProtectionServiceRequestBase
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataProtectionServiceRequestBase Class](dataprotectionservicerequestbase-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

