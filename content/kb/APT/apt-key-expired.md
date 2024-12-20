---
title: "apt key expired"
date: 2022-02-05T10:31:29-05:00
---
```
Knowledge Base Article - CTAC (Communications Training Analysis Corporation)  
=================================================

Subject: APT KEY EXPIRED ERROR

Revision History:
    2016-07-09 08:49:51 - Version 1 created by Paul Rigor

Details: (include steps to reproduce, symptoms, corrective actions, contact information, links and a any other helpful information)

 If you get an APT KEY EXPIRED message (first observed for Puppet APT repo), then do the following to repair it:

 apt-key list | grep expired

 < get the HEX value after the / >

apt-key adv --recv-keys --keyserver keys.gnupg.net < HEX value >

=================================================
This document is proprietary and confidential. No part of this document may be 
disclosed in any manner to a third party without the prior written consent of 
CTAC.```
