---
layout: post
title: "An Example of MGN and DMS"
author: NEEtojin
tags: AWS MGN DMS
---

(modified)

A short post about Application Migration Service (MGN) and Database Migration Service (DMS).

In my opinion, database migration should be done first.

**MGN**

|Status|Todo|Region|Service|
|---|---|---|---|
|Not ready|install replication agent|Source|EC2|
|Ready for testing|launch test instances|Target|MGN|
|Test in progress|test something|Target||
|Ready for cutover|launch cutover instances|Target|MGN|
|Cutover in progress|test something again|Target||
|Cutover complete||||

**DMS**

1. (Create replication instance ?)
1. Create endpoints, both source and target. (*EC2: Server name = DNS name)
1. Create task
