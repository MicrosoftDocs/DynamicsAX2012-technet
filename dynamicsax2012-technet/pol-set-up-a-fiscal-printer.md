---
title: (POL) Set up a fiscal printer
TOCTitle: (POL) Set up a fiscal printer
ms:assetid: fdf5e248-ddab-4632-868e-ea97fa667372
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711338(v=AX.60)
ms:contentKeyID: 49387155
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Set up a fiscal printer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A fiscal printer is a specific printer that must be certified for retail sales by the local tax authorities. All items that are sold must be registered through the printer. The fiscal printer is connected to the computer through a serial port.


> [!NOTE]
> <P>Verify whether your fiscal printer is supported in the local Polish market.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Fiscal printers** \> **Fiscal printers**.

2.  In the **Fiscal printers** form, in the **Fiscal printer** field, enter a unique code for the fiscal printer.

3.  In the **Fiscal printer type** field, select the printer type.

4.  In the **Description** field, enter a description of the fiscal printer.

5.  In the **Fiscal cash code** field, enter the number of the fiscal printer that is to be printed on the sales receipt.

6.  In the **COM port number** field, enter the number of COM port to which the fiscal printer is connected.

7.  In the **Certification of printer** field, select the type of operating system certification from the following options:
    
      - **No specification** – The fiscal printer operating system is not certified.
    
      - **Old certification** – The fiscal printer operating system is older than 1991.
    
      - **New certification** – The fiscal printer was assembled after 1991.

8.  Click **Fiscal tax codes** to open the **Sales tax codes** form, where you can associate fiscal tax codes to the existing sales tax codes.

## See also

[(POL) Fiscal printers (form)](https://technet.microsoft.com/en-us/library/jj711251\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

