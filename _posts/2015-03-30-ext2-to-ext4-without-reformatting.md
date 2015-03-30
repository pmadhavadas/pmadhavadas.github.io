---
layout: post
title: "Ext2 to Ext4 without reformatting"
date: 2015-03-30
---
## Ext2 to Ext4 without reformatting

1. log in as root

2. /usr/sbin/tune2fs -O extents,uninit_bg,dir_index,has_journal <drive>

3. /usr/sbin/e2fsck –pf <drive>
