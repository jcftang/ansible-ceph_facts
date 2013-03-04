## Start of ceph_facts (tested on bobtail)

This module currently dumps out facts for the ceph distributed object store.

- 'quorum_status' information (effectively 'mon' information)
- 'osd' information
    - Also the osd tree
- 'mds' information
- 'rados df' information

it assumes that the machine that is being logged into has the correct ceph
authentication/permissions setup
