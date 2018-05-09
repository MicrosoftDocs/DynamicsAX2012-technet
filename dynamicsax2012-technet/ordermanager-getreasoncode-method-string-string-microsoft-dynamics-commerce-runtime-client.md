---
title: OrderManager.GetReasonCode Method (String, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReasonCode Method (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReasonCode(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getreasoncode(v=AX.60)
ms:contentKeyID: 62213847
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonCode Method (String, String)

Gets the reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReasonCode ( _
    reasonCodeId As String, _
    locale As String _
) As IEnumerable(Of ReasonCode)
'Usage
Dim instance As OrderManager
Dim reasonCodeId As String
Dim locale As String
Dim returnValue As IEnumerable(Of ReasonCode)

returnValue = instance.GetReasonCode(reasonCodeId, _
    locale)
```

``` csharp
public IEnumerable<ReasonCode> GetReasonCode(
    string reasonCodeId,
    string locale
)
```

``` c++
public:
IEnumerable<ReasonCode^>^ GetReasonCode(
    String^ reasonCodeId, 
    String^ locale
)
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The reason code.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetReasonCode Overload](ordermanager-getreasoncode-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

