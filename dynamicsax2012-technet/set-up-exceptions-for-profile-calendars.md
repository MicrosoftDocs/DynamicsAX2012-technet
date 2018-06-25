---
title: Set up exceptions for profile calendars
TOCTitle: Set up exceptions for profile calendars
ms:assetid: d01e937c-b068-4de4-9844-5ed9e12c0dc6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550998(v=AX.60)
ms:contentKeyID: 43976727
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up exceptions for profile calendars [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up special days to manage exceptions to rules that are related to pay, and to attendance and absence registrations.

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Special days**.

2.  On the toolbar, click **New** to create a new line.

3.  In the **Special day** field, enter a name.

4.  In the **Description** field, enter a description.

5.  To integrate special days into pay agreements, select the **Special pay** check box.

6.  In the **Constant** field, enter the value to apply instead of the calculated pay time.
    

    > [!NOTE]
    > <P>This value is used as a factor on a related line in the <STRONG>Pay agreement lines</STRONG> form when the following conditions are true:</P>
    > <UL>
    > <LI>
    > <P>The <STRONG>Use fixed quantity</STRONG> check box is selected on the pay agreement line.</P>
    > <LI>
    > <P>An amount is not specified in the <STRONG>Constant</STRONG> field on the pay agreement line.</P>
    > <LI>
    > <P>The pay agreement line is delimited by the setup of this special day. This setup is typically used for a specific bonus that is not related to the number of work hours that the worker registers on the day.</P></LI></UL>



7.  In the **Absence code** field, select the absence code to associate with the special day. If workers do not make registrations on this day, this absence code is used.

## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About profile calendars for time and attendance registrations](about-profile-calendars-for-time-and-attendance-registrations.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

