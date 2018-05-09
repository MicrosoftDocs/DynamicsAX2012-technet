---
title: CommerceIdentity.LogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: LogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.LogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.logonconfiguration(v=AX.60)
ms:contentKeyID: 65321069
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.LogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# LogOnConfiguration Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnConfiguration As LogOnConfiguration
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As LogOnConfiguration

value = instance.LogOnConfiguration

instance.LogOnConfiguration = value
```

``` csharp
[DataMemberAttribute]
public LogOnConfiguration LogOnConfiguration { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnConfiguration LogOnConfiguration {
    LogOnConfiguration get ();
    void set (LogOnConfiguration value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

