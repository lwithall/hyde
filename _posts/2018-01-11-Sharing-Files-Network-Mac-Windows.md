---
layout: post
title: Sharing Files Between Mac and Windows
---

# How to share files network between Mac and Windows

Seems like a pretty simple requirement, but a little more tricky than first thought.

## Windows Setup

First, you need to enable file sharing in Windows in the homegroup.

## Mac

To the Mac machine to the Windows computer over [SMB](https://docs.microsoft.com/en-us/windows/desktop/fileio/microsoft-smb-protocol-and-cifs-protocol-overview).

To do that, go to the Finder and select the Go > Connect to Server (Cmd + K). 

Then, select smb://<ip address>, you will be prompted to login and the folder will be available on the Mac machine.
