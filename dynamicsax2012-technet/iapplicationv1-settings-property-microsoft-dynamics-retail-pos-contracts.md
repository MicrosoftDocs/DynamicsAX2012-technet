---
title: IApplicationV1.Settings Property  (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: Settings Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Settings
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.settings(v=AX.60)
ms:contentKeyID: 47129349
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.Settings
dev_langs:
- CSharp
- C++
- VB
---

# Settings Property

Get the application settings.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Settings As ISettings
    Get
'Usage
Dim instance As IApplicationV1
Dim value As ISettings

value = instance.Settings
```

``` csharp
ISettings Settings { get; }
```

``` c++
property ISettings^ Settings {
    ISettings^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Settings.ISettings](isettings-interface-microsoft-dynamics-retail-pos-contracts-settings.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Settings.ISettings](isettings-interface-microsoft-dynamics-retail-pos-contracts-settings.md) value.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

