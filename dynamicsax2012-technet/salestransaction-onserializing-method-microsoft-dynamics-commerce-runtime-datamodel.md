---
title: SalesTransaction.OnSerializing Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OnSerializing Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.OnSerializing(System.Runtime.Serialization.StreamingContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.onserializing(v=AX.60)
ms:contentKeyID: 65321175
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.OnSerializing
dev_langs:
- CSharp
- C++
- VB
---

# OnSerializing Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<OnSerializingAttribute> _
Public Sub OnSerializing ( _
    context As StreamingContext _
)
'Usage
Dim instance As SalesTransaction
Dim context As StreamingContext

instance.OnSerializing(context)
```

``` csharp
[OnSerializingAttribute]
public void OnSerializing(
    StreamingContext context
)
```

``` c++
[OnSerializingAttribute]
public:
void OnSerializing(
    StreamingContext context
)
```

#### Parameters

  - context  
    Type: [System.Runtime.Serialization.StreamingContext](https://technet.microsoft.com/library/t16abws5\(v=ax.60\))  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

