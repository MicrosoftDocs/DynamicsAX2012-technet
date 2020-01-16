---
title: Identify and resolve conflicts in segregation of duties
TOCTitle: Identify and resolve conflicts in segregation of duties
ms:assetid: 32a27e09-8db1-4dba-91ef-e5804360a66d
ms:mtpsurl: https://technet.microsoft.com/library/Hh556858(v=AX.60)
ms:contentKeyID: 39509588
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Identify and resolve conflicts in segregation of duties 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can set up rules to separate tasks that must be performed by different users. This concept is named segregation of duties. When the definition of a security role or the role assignments of a user violate the rules, the conflict is logged. All conflicts must be resolved by the administrator.

Use the procedures in this topic to identify and resolve conflicts that involve segregation of duties.

## Verify whether user role assignments comply with new rules for segregation of duties

When you assign users to roles, the rules for segregation of duties are automatically enforced. If you try to assign a user to roles that contain conflicting duties, you receive an error message. You must then resolve the conflict either by denying the role assignment or by overriding the conflict.

However, compliance is not verified when you create the rules for segregation of duties. Therefore, it is possible to create a rule that causes existing user role assignments to conflict. This means that you must validate compliance after you create new rules.

Use the **Verify compliance of user-role assignments with rules for segregation of duties** form to verify whether existing role memberships comply with the rules. You can run the verification process on demand or as a regularly scheduled batch job.


> [!WARNING]
> <P>When an Active Directory Domain Services group is assigned to a security role, Microsoft Dynamics AX is unable to calculate conflicts in segregation of duties for individual users who are part of the Active Directory Domain Services group.</P>



1.  Click **System administration** \> **Setup** \> **Security** \> **Segregation of duties** \> **Verify compliance of user-role assignments**.

2.  Follow one of these steps:
    
      - To run the verification process immediately, click **OK**. The **Infolog** form displays the results of the validation. If there is a conflict, you can double-click the message to open the **Users** form and change the user’s role assignments. Conflicts are also logged in the **Segregation of duties conflicts** form.
    
      - To run the verification process as a batch job, select **Batch processing**, and then set the other batch parameters. After the batch job runs, you can review the conflicts in the **Segregation of duties conflicts** form.

## View and resolve conflicting user role assignments

Use the **Segregation of duties conflicts** form to allow or deny role assignments that cause a conflict.

This form lists conflicts that are identified by the batch job that is run from the **Verify compliance of user-role assignments with rules for segregation of duties** form. This form also lists conflicts that occur when rules for automatic role assignment try to assign a user to two roles that contain conflicting duties.

1.  Click **System administration** \> **Setup** \> **Security** \> **Segregation of duties** \> **Segregation of duties conflicts**.
    
    –or–
    
    Click **System administration** \> **Setup** \> **Security** \> **Segregation of duties** \> **Segregation of duties unresolved conflicts**.

2.  Select a conflict, and then click one of the following buttons:
    
      - **Deny assignment** – Deny the assignment of the user to the additional security role. If you deny an automatic role assignment, the user is marked as excluded from the role. The excluded user is not granted the access that is associated with the role, and the user cannot be assigned to the role until the administrator removes the exclusion.
    
      - **Allow assignment** – Override the conflict, and allow the user to be assigned to both security roles. If you override a conflict, you must enter a reason in the **Reason for override** field.

## Verify whether existing roles comply with new rules for segregation of duties

When you create or modify a role, the rules for segregation of duties are automatically enforced. You cannot assign conflicting duties to a role.

However, compliance is not verified when you create the rules for segregation of duties. Therefore, it is possible to create a rule that causes an existing role definition to have a conflict. This means that you must validate compliance manually after you create new rules.

1.  Click **System administration** \> **Setup** \> **Security** \> **Segregation of duties** \> **Segregation of duties rules**.

2.  Select a rule, and then click **Validate duties and roles**.
    
    The **Infolog** form is displayed.
    
      - If any existing roles violate the selected rule, a message is displayed that contains the name of the role and the names of the conflicting duties. The administrator must either indicate the mitigation for the security risk or modify the role so that it does not violate the rules for segregation of duties.
    
      - If no roles violate the selected rule, a message indicates that all roles are in compliance.

## See also

[Set up segregation of duties](set-up-segregation-of-duties.md)

  


