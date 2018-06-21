---
title: Set up upload options for Synch Service messages
TOCTitle: Set up upload options for Synch Service messages
ms:assetid: e21945c3-f610-467b-8242-3edaa5aa027a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597264(v=AX.60)
ms:contentKeyID: 39519344
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up upload options for Synch Service messages [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Commerce Data Exchange: Real-time Service is used by Commerce Data Exchange: Synch Service to upload status messages to Microsoft Dynamics AX. You control whether this upload occurs, and how often it occurs, by selecting a set of upload options for each Synch Service profile. For more information about how to set up a profile, see [Set up a profile for Synch Service](set-up-a-profile-for-synch-service.md).


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



Complete the following procedure to create a set of upload options for Synch Service.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Commerce Data Exchange: Synch Service upload options**.

2.  In the **Commerce Data Exchange: Synch Service upload options** form, click **New** to create a new set of upload options.

3.  In the **Name** field, enter a name for the set of upload options.

4.  Select the **Upload enabled** check box if messages are uploaded to Microsoft Dynamics AX for instances of Synch Service that use these upload options. Clear the check box if messages are stored only in the message database for Synch Service at the store.

5.  Select the **Error message only** check box to upload only error messages. Clear the check box to upload status messages of all types. These status messages include error messages.

6.  In the **Interval (minutes)** field, enter the number of minutes between upload operations.

7.  Repeat steps 2 through 6 for any other set of upload options that you require.

8.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Commerce Data Exchange: Synch Service profiles**.

9.  Assign a set of upload options and a Real-time Service profile to each Synch Service profile.

10. Select each profile that upload options are assigned to, and then click **Send configuration**.

## See also

[Commerce Data Exchange: Synch Service upload options (form)](https://technet.microsoft.com/en-us/library/hh597138\(v=ax.60\))

[Commerce Data Exchange: Synch Service profiles (form)](https://technet.microsoft.com/en-us/library/hh597328\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

