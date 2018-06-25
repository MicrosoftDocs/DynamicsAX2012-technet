---
title: 'How to: Add a Service Operation to a Service'
TOCTitle: 'How to: Add a Service Operation to a Service'
ms:assetid: 5ab48644-23d8-467c-b59b-56c66d0c73d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa607052(v=AX.60)
ms:contentKeyID: 35244359
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add a Service Operation to a Service [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to add a custom service operation to a service in Application Integration Framework (AIF). Specifically, a new service operation is added to an existing document service class. However, you follow the same method to add a service operation to any class that is exposed as a service in Microsoft Dynamics AX. An example of a custom method included with Microsoft Dynamics AX on an existing document service is the TrvExpenseService.Submit method.

Document services that are included with Microsoft Dynamics AX can contain one or more of several service methods. You can select from these methods when you create a new document service using the [AIF Document Service Wizard](creating-new-document-services.md). You can also add service operations to any new or existing document service. Each document service class included with Microsoft Dynamics AX contains one or more of the following methods.

  - create

  - delete

  - find

  - findKeys

  - getKeys

  - getChangedKeys

  - read

  - update

These methods support document functionality that enables you to perform create, read, update, and delete operations on data in Microsoft Dynamics AX. For more information, see [Document Class Service Operations](document-class-service-operations.md).

## Add the Method to the Document Service Class

When adding a service operation, the first step is to add the method to the service class. As an example, we'll add a method to the CustCustomerService class. The new method adds two integers and returns the result.

1.  Open the AOT, expand the **Classes** node and locate the CustCustomerService class.

2.  Right-click the class, click **New**, and then click **Method**.

3.  In the **Editor** window, enter the following code.
    
        public int addIntegers(int _int1, int _int2)
        {
            return _int1 + _int2;
        }

4.  Press F7 to compile and then press CTRL+S to save your changes.

If you add a custom method to a document service that performs one of the create, read, delete, update, find, getKeys, getChangedKeys, or findKeys actions, you should add the appropriate method type attribute to the method. For more information, see [Method Type Attribute](method-type-attribute.md). You must also add the [SysEntryPointAttribute](https://technet.microsoft.com/en-us/library/gg958657\(v=ax.60\)) to any custom method. For more information, see [Setting SysEntryPointAttribute for Services](setting-sysentrypointattribute-for-services.md).

## Expose the Method as a Service Operation

1.  Open the AOT, expand the **Services** node, and locate the CustCustomerService service.

2.  Expand the service, right-click **Operations**, and then select **Add Operation**.

3.  In the **Add service operations** form, select the addIntegers method in the grid and select **Add**.

4.  Click **OK**.

5.  Press CTRL+S to save your changes.

## Registering the Service

After you have added the method and exposed it as a service operation, you must register the service in the AOT.

### To register the service in the AOT

1.  Open the AOT, expand the **Services** node, and then locate the CustCustomerService service.

2.  Right-click the service, click **Add-Ins**, and then click **Register service**.

3.  On the **Services** form, click **Refresh**.

Now you can expose the service on a basic port or an enhanced port. For more information about creating a basic integration port to expose service operations, see [Using Basic Integration Ports](using-basic-integration-ports.md). If you create a new enhanced port on the **Inbound ports** form, the addIntegers operation is available from the **Service operations** form. For more information about how to create and configure an enhanced inbound port, see [Managing integration ports](managing-integration-ports.md).

## See also

[About Document Service Classes](about-document-service-classes.md)

