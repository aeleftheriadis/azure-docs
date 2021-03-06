﻿---

title: Restore a deleted user in Azure Active Directory | Microsoft Docs
description: How to restore a deleted user, view restorable users, or permanently delete a user in Azure Active Directory
services: active-directory
documentationcenter: ''
author: curtand
manager: mtillman
editor: ''

ms.service: active-directory
ms.workload: identity
ms.tgt_pltfrm: 
ms.devlang: 
ms.topic: article
ms.date: 01/08/2018
ms.author: curtand                       
ms.reviewer: jeffsta
ms.custom: it-pro

---

# Restore a deleted user in Azure Active Directory

This article contains instructions to restore or permanently delete a previously deleted user. When you delete a user in the Azure Active Directory (Azure AD), the deleted user is retained for 30 days from the deletion date. During that time, the user and its properties can be restored. 

## Required permissions
The following permissions are sufficient to restore a user.

Role  | Permissions 
--------- | ---------
Company Administrator<p>Partner Tier1 Support<p>Partner Tier2 Support<p>User Account Administrator | Can restore deleted users 
Company Administrator<p>Partner Tier1 Support<p>Partner Tier2 Support<p>User Account Administrator | Can permanently delete users

## How to restore a deleted user

In the Azure portal, you can both restore a deleted user and permanently delete a deleted user.

1. In the [Azure AD admin center](https://aad.portal.azure.com), select **Users and groups** &gt; **All users**. 
2. Under **Show**, filter the page to show **Recently deleted users**. 
3. Select one or more recently deleted users.
4. Select **Restore user** or **Delete permanently**.

## Next steps
These articles provide additional information on Azure Active Directory user management.

* [Quickstart: Add or delete users to Azure Active Directory](add-users-azure-active-directory.md)
* [Manage user profiles](active-directory-users-profile-azure-portal.md)
* [Add guest users from another directory](active-directory-b2b-what-is-azure-ad-b2b.md) 
* [Assign a user to a role in your Azure AD](active-directory-users-assign-role-azure-portal.md)
