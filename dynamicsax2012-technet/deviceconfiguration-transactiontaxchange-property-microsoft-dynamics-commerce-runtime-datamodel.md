---
title: DeviceConfiguration.TransactionTaxChange Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionTaxChange Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TransactionTaxChange
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.transactiontaxchange(v=AX.60)
ms:contentKeyID: 62203198
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TransactionTaxChange
dev_langs:
- CSharp
- C++
- VB
---

# TransactionTaxChange Property

Gets or sets the transaction tax change reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRANSACTIONTAXCHANGE")> _
<DataMemberAttribute> _
Public Property TransactionTaxChange As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.TransactionTaxChange

instance.TransactionTaxChange = value
```

``` csharp
[ColumnAttribute("TRANSACTIONTAXCHANGE")]
[DataMemberAttribute]
public string TransactionTaxChange { get; set; }
```

``` c++
[ColumnAttribute(L"TRANSACTIONTAXCHANGE")]
[DataMemberAttribute]
public:
property String^ TransactionTaxChange {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The string containing the transaction tax change reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

