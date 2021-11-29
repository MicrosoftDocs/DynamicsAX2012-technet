---
title: Run AXUpdate in silent mode
TOCTitle: Run AXUpdate in silent mode
ms:assetid: 285a5e3b-f38d-4ba6-9ac7-e4a6dcac3a13
ms:mtpsurl: https://technet.microsoft.com/library/Hh538439(v=AX.60)
ms:contentKeyID: 39508861
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Run AXUpdate in silent mode 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you run AXUpdate.exe, by default the program runs the Update Setup Wizard. This wizard has a graphical user interface (GUI) that prompts you for required information. You can also run AXUpdate.exe at a command prompt, in silent mode. When AXUpdate.exe is run in silent mode, no GUI is displayed. Instead, you must supply all the required information at a command prompt when you start AXUpdate.exe. You can update any Microsoft Dynamics AX component in silent mode, if the update package that you are applying is appropriate for that component.


> [!NOTE]
> <P>A silent update is especially useful when you must update multiple clients at the same time. A mass update of clients resembles a mass deployment of clients. However, instead of using Setup.exe to deploy clients, you use AXUpdate.exe to update them. For more information, see <A href="mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md">Mass deployment of the Microsoft Dynamics AX Windows client</A>.</P>



## Determine which parameters to use

The same parameters are available when you enter them at a command prompt and when you create a parameter file.

For a list of the parameters for AXUpdate.exe, see [AXUpdate command line parameters reference](axupdate-command-line-parameters-reference.md).

## Specify update parameters at a command prompt

Use the following procedure to run the installation by entering parameters at a command prompt.

1.  Open a Command Prompt window.

2.  At the command prompt, type the following command:
    
    *\<Path to shared directory\>*\\AXUpdate.exe *parameter1*="*value*" *parameter2*="*value*"
    
    When you use multiple parameters, insert a single space between parameters.
    

    > [!WARNING]
    > <P>If you enter duplicate parameters, AXUpdate.exe fails silently.</P>



3.  After you have listed all parameters, press ENTER.

4.  After the installation is completed, review the log files that are created by AXUpdate.exe to verify the results of the update installation. By default, log files are saved to a subfolder of the **%ALLUSERSPROFILE%\\Microsoft\\Dynamics AX\\Dynamics AX Setup Logs** folder.

## Specify installation parameters by using a parameter file

Use the following procedure to run the installation by specifying a parameter file at a command prompt.

1.  Create a text file that lists the appropriate installation parameters and their values. In the parameter file, the *Name=Value* combination for each parameter must be on a separate line.
    

    > [!WARNING]
    > <P>If you enter duplicate parameters, Update fails silently.</P>

    
    Do not include double quotation marks in parameter files. Because the carriage return/line feed character is used as a delimiter in parameter files, values that usually require double quotation marks do not require them in parameter files.
    
    To prevent a line in a parameter file from being read, type a number sign (\#) at the start of the line. The line is now treated as a comment instead of a command or parameter.

2.  Open a Command Prompt window.

3.  At the command prompt, type the following command:
    
    *\<Path to shared directory\>*\\AXUpdate.exe ParmFile=\<*path of file*\\*FileName.txt*\>
    
    The path can be fully qualified or relative to the location of the AXUpdate.exe file. Relative paths can include upward qualifiers such as "..\\..\\".

4.  Press ENTER.

5.  After the installation is completed, review the log files that are created by AXUpdate.exe to verify the results of the update installation. By default, log files are saved to a subfolder of the **%ALLUSERSPROFILE%\\Microsoft\\Dynamics AX\\Dynamics AX Setup Logs** folder.

  


