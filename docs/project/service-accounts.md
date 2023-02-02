---
sidebar_position: 3
title: Service accounts
---

# Service accounts

A service account is a special kind of account that can be used by a external applications or services to manage resources within the project.

You can't use service accounts to log in to the system in the usual way. However, you can assign roles and permissions for these accounts, just as you do for regular accounts.

A list of service accounts can be found in the "Service accounts" section of the main menu. Press the **Create service account** button to create a new one.

When you create a new service account, you can specify a display name, comment, and its lifetime (e.g for one year). As a result of creating a service account, you will be issued a token that will allow you to make API requests on behalf of the account.

> **Attention!**
> For your protection, you should never share your token with anyone. If you have lost your token or it has been compromised, you can generate a new token for the account.
