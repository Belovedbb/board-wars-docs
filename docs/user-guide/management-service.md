---
layout: default
title: Management Service
parent: User Guide
nav_order: 3
---

# Management Service

Management service involves the management of user profiles as well as team based profiles.

## User
A user after being created from the [Auth Module]({{ site.baseurl }}{% link docs/user-guide/auth-module.md %}#auth-module) can perform other operations like:

* Creating or editing profile picture.
* Role assignment, usually from a top level role user
* Profile settings

## Team
A team is an aggregation of different users coming together for a specific function.
* Mandatory
    * Name: Unique Name of the team.
    * Status: If the status should be active or inactive.
    * Member Selection: Members of the team.
    * Leader: The leader of the team.
* Optional 
    * Color Code: Color code associated with the team.
    * Description: Description of team created.
