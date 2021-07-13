---
layout: default
title: Introduction
parent: Developer Guide
nav_order: 1
---
# Introduction
{: .no_toc_developer_guide }

## Table of contents
{: .no_toc_developer_guide .text-delta }

1. Introduction
{:no_toc_developer_guide}

---

## Starter
This section introduces building Board Wars and running it, either locally or remotely.

### Docker

We can build  Board Wars using docker. First, clone the repository from [Github](https://github.com/belovedbb/Board-wars), then run the command at the base directory
```sh
    docker-compose -f docker-compose.yml -f docker-compose.dev.yml up 
```
This will create all images needed (if not already created), and start them up as containers.

### Local Setup

Local setup involves building the project separately as a backend and frontend projects. Check out 
- [x] [Local Backend]({{ site.baseurl }}{% link docs/developer-guide/backend.md %}#backend)
- [x] [Local Frontend]({{ site.baseurl }}{% link docs/developer-guide/frontend.md %}#frontend)

### Post Setup

After setup, an organization has to be registered before any authentication, authorization or service operation is carried out.

To do that, we make use of github oauth organization registration. So, before a company is registered, it must have been created from github and linked to the application.

Also, a public email is required to track and link github organization email to local server email authentication.