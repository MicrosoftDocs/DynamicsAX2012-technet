---
title: HardwareProfileCashDrawer.UseCashDrawerPool Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseCashDrawerPool Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.UseCashDrawerPool
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.usecashdrawerpool(v=AX.60)
ms:contentKeyID: 65321250
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.UseCashDrawerPool
dev_langs:
- CSharp
- C++
- VB
---

# UseCashDrawerPool Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DRAWERUSECASHDRAWERPOOLVALUE")> _
Public Property UseCashDrawerPool As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawer
Dim value As Boolean

value = instance.UseCashDrawerPool

instance.UseCashDrawerPool = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DRAWERUSECASHDRAWERPOOLVALUE")]
public bool UseCashDrawerPool { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DRAWERUSECASHDRAWERPOOLVALUE")]
public:
property bool UseCashDrawerPool {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

