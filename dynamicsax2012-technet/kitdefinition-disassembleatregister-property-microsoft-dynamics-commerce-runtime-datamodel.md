---
title: KitDefinition.DisassembleAtRegister Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DisassembleAtRegister Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.DisassembleAtRegister
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitdefinition.disassembleatregister(v=AX.60)
ms:contentKeyID: 62210418
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition.DisassembleAtRegister
dev_langs:
- CSharp
- C++
- VB
---

# DisassembleAtRegister Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether disassembling the kit at a register is allowed or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISASSEMBLYATREGISTERALLOWED")> _
Public Property DisassembleAtRegister As Boolean
    Get
    Friend Set
'Usage
Dim instance As KitDefinition
Dim value As Boolean

value = instance.DisassembleAtRegister
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISASSEMBLYATREGISTERALLOWED")]
public bool DisassembleAtRegister { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISASSEMBLYATREGISTERALLOWED")]
public:
property bool DisassembleAtRegister {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[KitDefinition Class](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

