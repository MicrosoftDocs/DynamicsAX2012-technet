---
title: Manually install Retail Modern POS prerequisites
TOCTitle: Manually install Retail Modern POS prerequisites
ms:assetid: 661dc32b-0eae-470e-a21e-085d48e5b384
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741446(v=AX.60)
ms:contentKeyID: 62219722
ms.date: 06/08/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Manually install Retail Modern POS prerequisites [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use the information in this topic to install prerequisites for Retail Modern POS if you are installing on a Windows Server or Windows Embedded operating system. To ensure that you have installed all of the required prerequisites, you must install options 1 and 2, or option 3.

If you are installing Retail Modern POS on a supported Windows client operating system or a Windows RT operating system, these prerequisites are already installed.

This topic explains how to install the following prerequisites:

  - Windows Library for JavaScript (WinJS) (version 1.0.9600.16408 or higher)

  - Microsoft Visual C++ Runtime Package (VCLibs) (version 12.0.2.1005.1 or higher)

## Option 1: Download Visual C++ Runtime Package from the Microsoft Download Center

The Visual C++ Runtime Package is available as a download.

If you use this option to install the Visual C++ Runtime package, you’ll still need to install Windows Library for JavaScript using one of the other methods described in this topic.

Complete the following procedure to download and install the Visual C++ Runtime Package.

1.  Download the component from the following location: [Visual C++ Runtime Package](http://go.microsoft.com/fwlink/?linkid=511069).

2.  Open a Windows PowerShell session as an administrator.

3.  Install the 32-bit (x86) version of VCLibs by running the following command.
    
    ``` powershell
    Add-AppxPackage "<File path>\Microsoft.VCLibs.120.00_12.0.21005.1_x86__8wekyb3d8bbwe.appx"
    ```

## Option 2: Install another Windows app that includes the prerequisites

The prerequisites are installed with the MSN News app from the Windows Store. To obtain the prerequisites, you can download this app onto the computer where you plan to install Retail Modern POS.

Complete the following procedure to download the MSN News app.

1.  If you are using a server operating system, use the **Add Roles and Features** Wizard to add the **Desktop Experience** feature that is available under **User Interfaces and Infrastructure**. This enables you to access the Windows Store.

2.  Sign in with a Microsoft Account. To download apps from the Windows Store, you must sign in.

3.  In the Windows Store, find the app and install it on the computer.

## Option 3: Install Microsoft Visual Studio Express 2013 and manually install the prerequisites

You can install Visual Studio Express 2013 to obtain the files, and then manually install the prerequisites for Retail Modern POS.

1.  Download and install [Visual Studio Express 2013](http://go.microsoft.com/fwlink/?linkid=396853).

2.  Copy and paste the following files to the specified locations.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>File</p></th>
    <th><p>Copy from</p></th>
    <th><p>Paste to</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Microsoft.WinJS.2.0.appx</strong></p></td>
    <td><p>\Program Files (x86)\Microsoft SDKs\Windows\v8.1\ExtensionSDKs\Microsoft.WinJS.2.0\1.0\</p></td>
    <td><p>\Program Files (x86)\Microsoft Dynamics AX\60\Retail Modern POS\x64\Dependencies\</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Microsoft.VCLibs.x86.12.00.appx</strong></p>
    <p>(32-bit operating systems only)</p></td>
    <td><p>\Program Files (x86)\Microsoft SDKs\Windows\v8.1\ExtensionSDKs\Microsoft.VCLibs\12.0\AppX\Retail\x86\</p></td>
    <td><p>\Program Files (x86)\Microsoft Dynamics AX\60\Retail Modern POS\x86\Dependencies\x86\</p></td>
    </tr>
    </tbody>
    </table>


3.  Manually install the prerequisites.
    
    1.  Open a Windows PowerShell session as an administrator.
    
    2.  Run the following command to install WinJS.
        
        ``` powershell
        Add-AppxPackage "<Drive>:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Modern POS\x64\Dependencies\Microsoft.WinJS.2.0.appx"
        ```
    
    3.  Run the following command to install VCLibs.
        
        ``` powershell
        Add-AppxPackage "<Drive>:\Program Files (x86)\Microsoft Dynamics AX\60\Retail Modern POS\x86\Dependencies\x86\Microsoft.VCLibs.x86.12.00.appx"
        ```

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

