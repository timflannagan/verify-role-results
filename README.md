Purpose:
===========
- Run this role after the tasks/main.yml task flow to ensure that
  the previously run role results were properly executed.

To-Do:
===========
1. Run verify-present-mount.yml in a VM to check that disk verification works
3. Figure out if conditional checks are necessary in the verify-* files
4. Figure out if only checking for an absent device in /etc/fstab is enough
   for verifying an absent device
