---
date: "2014-08-08T11:17:38Z"
title: "aptly repo"
menu:
    doc:
        parent: Commands
        weight: 20
---

aptly repo
----------

Local repository is a collection of packages (most usually custom packages created internally).
Packages could be added to local repository at any moment, removed, moved or copied between repos.
Multiple versions of the same package could be added to the repository.
In order to capture current repository state, [create snapshot](/doc/aptly/snapshot/create/).

Local repositories could be published either [directly](/doc/aptly/publish/repo/)
or from [snapshot](/doc/aptly/publish/snapshot).