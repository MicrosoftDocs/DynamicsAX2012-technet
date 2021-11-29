---
title: Configure a channel database for large data volumes
TOCTitle: Configure a channel database for large data volumes
ms:assetid: 7f2b350c-ef2c-4676-b082-2e1e50d797d2
ms:mtpsurl: https://technet.microsoft.com/library/Mt807868(v=AX.60)
ms:contentKeyID: 74436957
author: Khairunj
ms.date: 04/04/2017
mtps_version: v=AX.60
---

# Configure a channel database for large data volumes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


If your organization has many channel databases that are frequently updated, consider asking Microsoft support if your organization is a candidate to configure your environment for large data volumes. Candidates for using this functionality typically have over 500,000 changes per hour in their databases.

With the release of KB 3208541, Microsoft provides support for approved customers to add a configuration that optimizes change tracking across channel data groups.

To use this feature, you must install KB 320851 so that you can activate the feature and have access to the Shared change tracking staging tables. Then you need to configure shared change tracking for a distribution schedule for your large volume data groups.

You can create additional change tracking staging tables to meet your organization’s needs.

## Install KB 3208541

Download and install hotfix 3208541 from Dynamics Lifecycle Services. For instructions, see [Apply updates and hotfixes](apply-updates-and-hotfixes.md).

## Configure shared change tracking

1.  Open the **Distribution schedule** form (**Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**).

2.  Right-click the form in an area in which there are no controls, and click **Personalize**.

3.  In the **Personalization** form, under **Layout**, expand **Body** \> **DetailsContainer** \> **DetailsHeader**, and then click **Add fields**.
    
    ![Add fields](images/Mt807868.addfields(AX.60).png "Add fields")

4.  In the **Select field** list, expand **Distribution schedule**, select **Shared change tracking staging table**, click **Add**, and then close the **Select field** list.

5.  In the **Layout** window, make sure that **Shared change tracking staging table** is selected, and then click **Down**, until it is after **Direction of data flow** under **DetailsHeader**.
    
    ![Adjust down](images/Mt807868.Adjustdown(AX.60).png "Adjust down")

6.  Close the **Personalization** window.

7.  Close and then reopen the **Distribution schedule** form.

8.  Select a 1020 schedule. In the **Shared change tracking staging table** field, enter **RetailCDXSharedChangeTracking\_Price**, and then click **Save**.

9.  If your system is still running defaults, you will get the error “RetailGroupMemberLine subjob cannot be contained in multiple jobs.”
    
    Remove the RetailGroupMemberLine subjob from the 1020 schedule. This error occurs because this subjob is already included in the 1040 job.

10. Click **Save**.

## Requirements for using shared change tracking

When this feature is enabled, customers should be aware of the following requirements that Microsoft will be enforcing.

  - If a distribution schedule has shared change tracking enabled, and the schedule associates channel data group X and job Y, this schedule will be the only schedule allowed that synchronizes job Y with data group X.
    
      - Related sub-jobs that belong to the job linked to this schedule cannot be included in multiple jobs.
    
      - All channel data groups that should receive data for this job must be included in this schedule.

  - If a distribution schedule has shared change tracking enabled, only one execution instance is allowed.
    

    > [!NOTE]
    > <P>If a batch job has been set up, do not click the <STRONG>Run now</STRONG> button on the <STRONG>Distribution schedule</STRONG> form. This can conflict with the batch job and cause inconsistent data issues.</P>



  - Each shared change tracking staging table can only be used by at most one distribution schedule, to avoid read/write contention.

## Staging tables

Microsoft ships the following staging tables for prices and product schedule, respectively:

  - RetailCDXSharedChangeTracking\_Price

  - RetailCDXSharedChangeTracking\_Product

If you need more staging tables, you can create them by duplicating the template table: **RetailCDXSharedChangeTracking\_Template**.

In the AOT, find **RetailCDXSharedChangeTracking\_Template**, copy it, and rename it.

  


