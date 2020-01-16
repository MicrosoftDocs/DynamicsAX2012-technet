---
title: About creating alert rules
TOCTitle: About creating alert rules
ms:assetid: 8daa1191-386b-4392-b194-21742698f73b
ms:mtpsurl: https://technet.microsoft.com/library/Aa834415(v=AX.60)
ms:contentKeyID: 46687554
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About creating alert rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create alert rules, consider the following conditions.

## Creating alert rules

New or modified alert rules are accepted only if users have access to all tables and fields that are required to use the rules.

For example, a user creates a rule on a table for which he currently has appropriate security permissions. However, if the user's security permissions are later limited, the user cannot access the table on which he created the rule.

The rule remains visible in the **Manage alert rules** form, but no alerts that are based on this rule are generated or sent to the user.

The same situation occurs if a user creates rule on a table, and the filter of the rule contains a reference to another table. If the user's permissions to the referenced table are removed or denied, the alert rule becomes obsolete, and no alerts are generated from this rule.

## Creating alert rules that are based on templates

A user who wants to create a new rule from a template can select templates only for those parts of Microsoft Dynamics AX that he or she has permission to use.

## Creating alert rules that involve setup of an inquiry

In general, if all the tables that are listed in an inquiry form have either a 1:n or an n:1 relationship with the table that was originally selected, specific rights and limitations apply to the user of the inquiry feature. When an alert rule is created that has a filter in an inquiry form, the same rights and limitations apply to the owner of the rule.

## Creating alert rules on foreign keys

A rule that is set up on a foreign key does not generate alerts if the foreign key is renamed as part of a rename-primary-key operation. A foreign key is a field that is referenced in one form, and that represents a primary key in another form. As the name rename-primary-key operation implies, the field is renamed in the form in which it originates.

For example, you have a service agreement that is attached to the service agreement group that is named Denmark. In the **Service agreements** form, you set up an alert rule on the service agreement, so that you are alerted if the name of the Denmark service agreement group changes. If the name of the service agreement group is later changed to the name of another existing group, such as Sweden, you receive an alert. However, you do not receive an alert if the name of the Denmark service agreement group is changed by a rename-primary-key operation. When a rename-primary-key operation is used, the name of the service agreement group is changed in the form where the group is set up, the **Service agreement groups** form. For example, a rename-primary-key operation might change the name of the service agreement group from Denmark to DK. However, this change does not trigger an alert.

## Virtual companies

Alert rules must be set up on each company in a virtual company. One alert rule cannot apply to more than one company in a virtual company.

## Deleted users

If a user is deleted, all alert rules that are owned by that user are also deleted.

If a user must be deleted, but you want to preserve an alert rule that the user created, you must change the user identification of the alert rule before you delete the user. Alternatively, to preserve all rules that the user created, do not delete the user. Instead, just disable the user. The alert rules of a user who has been disabled instead of deleted are preserved.

## See also

[About alert rules](about-alert-rules.md)

  


