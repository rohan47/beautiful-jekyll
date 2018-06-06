---
layout: post
title: GSoC 2018 Coding Period Week Two and Three
image: /img/coding.jpeg
---

These two weeks were amazing, learned a lot during this time.  
Created the prototype of the design doc and created a [Pull Request](https://github.com/rook/rook/pull/1740) to initiate review. The PR got comments and I updated the design accordingly which finally got merged.  

The design focuses on how user will use Rook to provision NFS volume and consume the volume. To demonstrate this there are sample CRD instance examples which explores options which a user will use to configure the NFS server and example on how to consume the NFS volume.

Here is the [design doc](https://github.com/rook/rook/blob/master/design/nfs.md).

My progress for the Phase one of the Coding Period:  
Design document 1-pager (2-4 weeks)
- [x] Investigate related technology such as Kubernetes, NFS servers, volume provisioning, etc.
- [x] Identify full scope and requirements of feature
- [x] Prototype as needed to explore potential implementation choices and trade-offs
- [x] Write detailed design document that specifies how feature will be implemented and tested
- [x] Submit a pull request for the design, integrate feedback and have it approved and merged to master

Coding implementation (8-10 weeks)  
User facing experience (1 week)
- [ ] New types, custom resources, and config options to capture the full experience for a user to setup and configure NFS storage with Rook
