---
layout: post
title: "Ext2 to Ext4 without reformatting"
date: 2015-03-30
---
## Ext2 to Ext4 without reformatting

* log in as root

* /usr/sbin/tune2fs -O extents,uninit_bg,dir_index,has_journal <drive>

* /usr/sbin/e2fsck –pf <drive>
