---
title: IPosLegacyApp Interface (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: IPosLegacyApp Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.IPosLegacyApp
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iposlegacyapp(v=AX.60)
ms:contentKeyID: 47128210
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.IPosLegacyApp
dev_langs:
- CSharp
- C++
- VB
---

# IPosLegacyApp Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Do not use this interface. It is for internal use only.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("0F01AF5C-33C6-4A97-BAAB-F932A71EDEEF")> _
Public Interface IPosLegacyApp
'Usage
Dim instance As IPosLegacyApp
```

``` csharp
[GuidAttribute("0F01AF5C-33C6-4A97-BAAB-F932A71EDEEF")]
public interface IPosLegacyApp
```

``` c++
[GuidAttribute(L"0F01AF5C-33C6-4A97-BAAB-F932A71EDEEF")]
public interface class IPosLegacyApp
```

## Remarks

This interface is neither implemented by any service nor exposed to service via IApplication.

To save time, we composed internal legacy app in PosApplication for internal purpose. (Not exposed via IApplication) With time, we will merge POSApp class (Implementing this interface) to PosApplication in SystemCore and can remove this interface.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)

