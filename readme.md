---
title: "Docker Example Solution Brief"
summary: "Docker Solution Briefs enable you to integrate the Docker container platform with popular 3rd party ecosystem solutions. This Solution Brief is a self-documenting guide to writing your own. Clone
this repo and go. Make sure to edit these tags."
type: guide
author: khudgins
visibleto: loggedinleads
campaign: "docker-certified-infrastructure"
product:
  - ee
testedon:
  - "ee-17.06.2-ee-7"
  - "ucp-2.2.5"
  - "dtr-2.4.2"
platform:
  - linux
tags:
  - "solution-brief"
  - storage
dateModified: "2018-04-24T13:24:21+00:00"
dateModified_unix: 1524576261
uniqueid: KB000669
---
## Overview

Docker Solution Briefs enable you to integrate the Docker Enterprise Edition (EE) container platform with popular 3rd party ecosystem solutions for networking, load balancing, storage, logging and monitoring, access management, and more.

Add a description of your solution brief here. You should include a short blurb of your product and how it integrates with Docker.

## Prerequisites

List the assets that your users need to successfully complete the tasks in your solution brief. Include links to related Docker Solution Briefs or install guides to describe the beginning state of the users environment that you require to complete your instructions.

As an example (edit this to fit your requirements):

- [Docker EE 17.06 Platform on VMware vSphere](https://success.docker.com/article/vsphere-storage/)
- VSphere 6.0
- Linux kernel 4.2.1 minimum

## Installation and Configuration

Start your brief by cloning this repository. You don't have to fork it - just clone it (or make a reasonable facsimile) and set up your own repository. Docker needs access to it for submodule inclusion into our publishing release process.

Provide detailed, step-by-step instructions for your Solution Brief here. If there is automation involved, then start with the inclusion of your automation code into a Docker EE deployment, and then how to make sure the automation run starts correctly.

1. First step:
    Include shell and/or code snippets for each step

    ```
    % git clone git@github.com/docker/dci-brief-example
    ```

2. Second step:
    Set up your own git repository hosting. For example, if you're using GitHub, log in and create a new repo. Then, point your cloned copy of our sample to the new, empty repository in GitHub:

    ```
    git remote add origin git@github.com:yourcompany/name_of_your_new_solution_brief
    git push -u origin master
    ```

3. Third step:
    Use this readme.md file as an example, and write your own procedural docs to install/integrate your product with Docker EE:

    ```
    vi readme.md
    git commit -m "updated some docs"
    ```

    Make sure to use step-by-step examples:

    ```
    % docker info
    ```

    and include output when necessary:

    ```
    Containers: 0
    Running: 0
    Paused: 0
    Stopped: 0
    Images: 0
    Server Version: 17.12.0-ce
    ...

    Experimental: true
    Insecure Registries:
     127.0.0.0/8
    Live Restore Enabled: false
    ```


## Best Practice Recommendations

When updating your solution brief, Docker should automatically pull in your changes during our documentation releases. In the event you need to get the content published faster (ie: bugfix issues), contact your Docker partner representative so they can notify the publishing team.

## Monitoring and Troubleshooting

Add operational instructions as needed. If there are any gotchas or difficult parts, troubleshooting advice goes here as well.

## Further Reading

Refer to the following links for additional information:

- <https://github.com/vmware/vsphere-storage-for-docker>
- <http://vmware.github.io/vsphere-storage-for-docker/documentation/>
- <https://bintray.com/vmware/vDVS/VIB/>
