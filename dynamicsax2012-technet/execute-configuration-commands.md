---
title: Execute configuration commands
TOCTitle: Execute configuration commands
ms:assetid: a18308bc-4a72-48e1-8661-c1ec390282bd
ms:mtpsurl: https://technet.microsoft.com/library/Aa569627(v=AX.60)
ms:contentKeyID: 36941326
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Execute configuration commands 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to use configuration commands to set the options that are used when a Microsoft Dynamics AX client or an instance of Application Object Server (AOS) starts.


> [!WARNING]
> <P>If you make changes in the Microsoft Dynamics AX 2012 Server Configuration utility, the system prompts you to restart the AOS instance. The restart affects all Microsoft Dynamics AX client and database connections to the AOS instance. If you must perform one or more of these procedures on a production server, we recommend that you perform the procedures during off-peak hours to prevent dropped connections for clients and databases.</P>



You can run configuration commands from the following locations:

  - In the **Configuration Command to run at kernel startup** field in the Microsoft Dynamics AX 2012 Configuration utility or the Microsoft Dynamics AX 2012 Server Configuration utility

  - At a command prompt

  - In a configuration file

## Run a command from the kernel startup field

You can run a configuration command by using the **Configuration Command to run at kernel startup** field in the Microsoft Dynamics AX 2012 Configuration utility or the Microsoft Dynamics AX 2012 Server Configuration utility.


> [!NOTE]
> <P>The Microsoft Dynamics AX 2012 configuration utilities do not check syntax before they run configuration commands in the kernel. We recommend that you test all commands before you use them in a production environment.</P>



1.  Open a configuration utility. Click **Start** \> **All Programs** \> **Control Panel** \> **Administration** \> **Microsoft Dynamics AX 2012 Configuration** –or– **Microsoft Dynamics AX 2012 Server Configuration**.

2.  In the **Configuration Command to run at kernel startup** field, enter a configuration command in the format **-command=value**.
    

    > [!NOTE]
    > <P>You cannot modify the original configuration of a system. Therefore, all the fields in the original configuration are unavailable. To change settings, you must create and modify a new configuration. For more information about how to create a new configuration, see <A href="manage-a-client-configuration.md">Manage a client configuration</A> or <A href="manage-an-aos-configuration.md">Manage an AOS configuration</A>.</P>

    
    To enter more than one command, leave a space between commands. For example, enter two commands as follows: **-command=value -command2=value**

3.  Save the configuration, and close the configuration utility.

## Run a client configuration command at a command prompt

If you start a client at a command prompt, you can pass the configuration commands that are used when the instance starts.

1.  Open a Command Prompt window. Click **Start** \> **All Programs** \> **Accessories** \> **Command Prompt**. Locate the directory in which Microsoft Dynamics AX is installed. By default, the following directory is used for the client:
    
    C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Client\\Bin

2.  Type **Ax32.exe** followed by a configuration command, as follows:
    
    **Ax32.exe -command=value**
    
    Press ENTER to start the Microsoft Dynamics AX client in the specified configuration.

## Run a server configuration command at a command prompt

If you start an AOS instance at a command prompt, you can pass the configuration commands that are used when the instance starts.

1.  Open a Command Prompt window. Click **Start** \> **All Programs** \> **Accessories** \> **Command Prompt**. Locate the directory in which Microsoft Dynamics AX is installed. By default, the following directory is used:
    
    C:\\Program Files\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin

2.  Type **Ax32Serv.exe** followed by a configuration command, as follows:
    
    **Ax32Serve.exe -command=value**
    
    Press ENTER to start the AOS instance in the specified configuration.

## Add a configuration command to a configuration file

1.  Open a configuration utility. Click **Start** \> **All Programs** \> **Control Panel** \> **Administration** \> **Microsoft Dynamics AX 2012 Configuration** –or– **Microsoft Dynamics AX 2012 Server Configuration**.

2.  Click **Manage**, and then click **Save configuration to a file**. Enter a location and name for the configuration file, and then click **Save**.
    
    The configuration is saved as an **.axc** file.

3.  Close the configuration utility.

4.  In a text editor such as Notepad, open the client configuration file that you are using.

5.  Modify any configuration command that you want to change the value of, or add a configuration command that does not have an interface element. Use commands in the format command,data type,value.

6.  Save and close the configuration file.

7.  Close any client or AOS instance that is using the configuration file, and then restart the client or AOS instance.

## See also

[Client configuration commands](client-configuration-commands.md)

[Application Object Server (AOS) configuration commands](application-object-server-aos-configuration-commands.md)

  


