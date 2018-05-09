---
title: StorageErrors Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: StorageErrors Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.StorageErrors
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.storageerrors(v=AX.60)
ms:contentKeyID: 49832002
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.StorageErrors
dev_langs:
- CSharp
- C++
- VB
---

# StorageErrors Class

Class container for all errors resulting from storage operations in the runtime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class StorageErrors
'Usage
You do not need to declare an instance of a static class in order to access its members.
```

``` csharp
public static class StorageErrors
```

``` c++
public ref class StorageErrors abstract sealed
```

## Remarks

When adding a new constant, modifying the name of a constant, or deleting a constant, a corresponding change needs to be made in all files below: - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\SharePoint\\StoreFront\\Services\\ServiceResources.resx (StoreFront) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\Framework\\Assets\\Strings\\{locale}\\resources.resjson (mPOS) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\Framework\\Core\\ErrorHelper.ts (mPOS) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\WindowsPhone\\C1\\Pos\\Model\\Exceptions\\DataValidationErrors.cs (Win Phone POS) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\WindowsPhone\\C1\\Pos\\Application\\Resources\\AppResources.resx (Win Phone POS) so a proper UI message is displayed.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.StorageErrors  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

