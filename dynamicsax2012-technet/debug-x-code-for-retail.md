---
title: Debug X++ Code for Retail
TOCTitle: Debug X++ Code for Retail
ms:assetid: b0b29edb-d132-4876-8b6d-551bb4929976
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126099(v=AX.60)
ms:contentKeyID: 52075234
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Debug X++ Code for Retail [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can use the X++ debugger to debug from Microsoft Dynamics AX for Retail POS to Commerce Data Exchange: Real-time Service to Microsoft Dynamics AX, or from commerce runtime to Real-time Service to Microsoft Dynamics AX. Perform the following steps to debug code that runs on the client:

  - Create a local client configuration.

  - Create a Business Connector configuration.

  - Update the Business Connector configuration in the registry editor.

Then you can set breakpoints in your X++ code and begin debugging.


> [!WARNING]
> <P>To debug code that runs on the server, you must also configure debugging on the AOS server. For more information, see <A href="https://technet.microsoft.com/en-us/library/bb190066(v=ax.60)">How to: Debug X++ Code Running in .NET Business Connector</A>.</P>



### To Create a Local Client Configuration

1.  Open **Microsoft Dynamics AX 2012 Configuration**.

2.  In **Configuration Target**, select **Local client**.

3.  Click **Manage**, and then click **Create configuration…**

4.  Enter a configuration name. For example, DebugClient.

5.  Select **Active configuration**, and then click **OK**.

6.  Click the **Developer** tab. Select **Enable user breakpoints to debug code in the Business Connector**.

### To Create a Business Connector Configuration

1.  If you are not already in the **Microsoft Dynamics AX Configuration Utility** form, open **Microsoft Dynamics AX 2012 Configuration**.

2.  In **Configuration Target**, select **Business Connector (non-interactive use only)**.

3.  Click **Manage**, and then click **Create configuration…**

4.  Enter a configuration name. For example, DebugBCNet.

5.  Select **Active configuration**, and then click **OK**.

6.  Click the **Developer** tab. Select **Enable user breakpoints to debug code in the Business Connector**.

7.  Close the utility.

### To Update the Registry Editor

1.  Open **Windows Command Processor**.

2.  Enter regedit.exe.

3.  Right-click the key that corresponds to the Business Connector configuration you created in the previous procedure, point to **New**, and then click **String value**.
    

    > [!NOTE]
    > <P>For example, HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Dynamics\6.0\Configuration\DebugBCNet.</P>



4.  Right-click the new value, and then click **Rename**. Enter debug\_across\_os\_session.

5.  Double-click **debug\_across\_os\_session**.

6.  In **Value data**, enter 1. Click **OK**.

7.  In Windows Command Processor, enter IISReset, and then press **Enter**.

## See also

[Microsoft Dynamics AX Debugger](https://technet.microsoft.com/en-us/library/aa569668\(v=ax.60\))

[How to: Debug X++ Code Running in .NET Business Connector](https://technet.microsoft.com/en-us/library/bb190066\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

