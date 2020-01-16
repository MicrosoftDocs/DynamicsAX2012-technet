---
title: Run Setup in silent mode
TOCTitle: Run Setup in silent mode
ms:assetid: 3a6d1a25-d682-4056-8547-7b68b0f47523
ms:mtpsurl: https://technet.microsoft.com/library/Aa496627(v=AX.60)
ms:contentKeyID: 35132607
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Run Setup in silent mode 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you run the Setup wizard, Setup is running in interactive mode. In other words, a graphical user interface (GUI) prompts you for the required information. Alternatively, you can run Setup in silent mode. When Setup runs in silent mode, no GUI is displayed. Instead, you supply the required information at the command prompt or in a parameter file. You can install any Microsoft Dynamics AX component in silent mode.


> [!NOTE]
> <P>A silent installation is especially useful when you deploy multiple clients at the same time. For more information, see <A href="mass-deployment-of-the-microsoft-dynamics-ax-windows-client.md">Mass deployment of the Microsoft Dynamics AX Windows client</A>.</P>



## Determine which parameters to use

The same parameters are available whether you enter them at the command prompt or create a parameter file.

To determine which Microsoft Dynamics AX Setup parameters you want to use, we recommend that you review the example parameter file that is included on the Microsoft Dynamics AX DVD. The file is located at *\<Path to DVD or shared directory\>*\\Support\\ExampleParmFile.txt. For more information about individual parameters, see the [Setup parameters reference](setup-parameters-reference.md) on TechNet.

Microsoft Dynamics AX Setup can configure some required prerequisites, such as operating system features and roles and redistributable components that are on the Microsoft Dynamics AX installation media. If you want Setup to automatically configure these prerequisites, include the parameter *ConfigurePrerequisites=1*.

You can install other prerequisites silently by running the individual programs from the command line. To determine the command-line parameters that you want to use, we recommend that you run the stand-alone prerequisite validation utility on a representative client. When you use the utility to configure prerequisites, the log file indicates the commands that were used. By default, the log file is located at *\<Drive\>*\\Users\\*\<UserName\>*\\AppData\\Local\\Microsoft Dynamics AX 6\\Prerequisite Utility Logs\\*Date Time*\\Log.txt.

## Specify installation parameters at the command prompt

Use the following procedure to run the installation by entering parameters at the command prompt.

1.  Open a Command Prompt window.

2.  At the command prompt, type the following command:
    
    *\<Path to DVD or shared directory\>*\\Setup.exe *parameter1*="*value*" *parameter2*="*value*"
    
    When you use multiple parameters, insert a single space between parameters.
    

    > [!WARNING]
    > <P>If you enter duplicate parameters, Setup fails silently.</P>



3.  After you have listed all parameters, press ENTER.

## Specify installation parameters by using a parameter file

Use the following procedure to run the installation by specifying a parameter file at the command prompt.

1.  Create a text file that lists the appropriate installation parameters and their values. In the parameter file, the *Name=Value* combination for each parameter must be on a separate line.
    

    > [!WARNING]
    > <P>If you enter duplicate parameters, Setup fails silently.</P>

    
    Do not include double quotation marks in parameter files. Because the carriage return is used as a delimiter in a parameter file, values that usually require double quotation marks do not require them here.
    
    To prevent a line in a parameter file from being read, type a number sign (\#) before the line. The line is now treated as a comment instead of a command or parameter.

2.  Open a Command Prompt window.

3.  At the command prompt, type the following command:
    
    *\<Path to DVD or shared directory\>*\\Setup.exe ParmFile=\<*path of file*\\*FileName.txt*\>
    
    The path can be fully qualified or relative to the location of the Setup.exe file. Relative paths can include upward qualifiers such as "..\\..\\".

4.  Press ENTER.

  


