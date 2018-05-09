---
title: HardwareProfileCashDrawer.CashDrawerPoolId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashDrawerPoolId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.CashDrawerPoolId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.cashdrawerpoolid(v=AX.60)
ms:contentKeyID: 65319918
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.CashDrawerPoolId
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawerPoolId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DRAWERDEVICEPOOLVALUE")> _
Public Property CashDrawerPoolId As Long
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawer
Dim value As Long

value = instance.CashDrawerPoolId

instance.CashDrawerPoolId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DRAWERDEVICEPOOLVALUE")]
public long CashDrawerPoolId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DRAWERDEVICEPOOLVALUE")]
public:
property long long CashDrawerPoolId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

