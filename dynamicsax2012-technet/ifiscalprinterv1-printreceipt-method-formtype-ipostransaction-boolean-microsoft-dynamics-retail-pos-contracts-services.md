---
title: IFiscalPrinterV1.PrintReceipt Method (FormType, IPosTransaction, Boolean) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintReceipt Method (FormType, IPosTransaction, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintReceipt(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.printreceipt(v=AX.60)
ms:contentKeyID: 62206014
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PrintReceipt Method (FormType, IPosTransaction, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Print the standard slip, returns false if printing should be aborted altogether.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PrintReceipt ( _
    formType As FormType, _
    posTransaction As IPosTransaction, _
    copyReceipt As Boolean _
) As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim formType As FormType
Dim posTransaction As IPosTransaction
Dim copyReceipt As Boolean
Dim returnValue As Boolean

returnValue = instance.PrintReceipt(formType, _
    posTransaction, copyReceipt)
```

``` csharp
bool PrintReceipt(
    FormType formType,
    IPosTransaction posTransaction,
    bool copyReceipt
)
```

``` c++
bool PrintReceipt(
    FormType formType, 
    IPosTransaction^ posTransaction, 
    bool copyReceipt
)
```

#### Parameters

  - formType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType](formtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[PrintReceipt Overload](ifiscalprinterv1-printreceipt-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

