---
title: Cache
permalink: /project/computerArchitectureLearningNote/Cache
layout: single
author_profile: true
---

Caches are a kind of component that temporarily stores data near computing units for faster data access operations. In computer architecture, caches serve as an excessive, connecting computing units and disks together. Compared to disks, caches have faster access speed but smaller storage size. Therefore, frequently used data will be stored in caches temporarily.

The cache consists of three parts:
(1) a control unit that receives and returns control messages from the command processor, playing a critical role in page migration handling;
(2) an MSHR (Miss Status Holding Register), which is a set of registers used to coalesce multiple outstanding memory requests targeting the same data;
(3) a storage unit that holds cached data, organized according to specific replacement and placement policies.

