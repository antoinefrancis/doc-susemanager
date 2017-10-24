## System Details {#system-details}

When systems are registered to SUSE Manager, they are displayed on the Systems+Overview page. Here and on any other page, clicking the name takes you to the System Details page of the client, where all kinds of administrative tasks can be performed, including the removal of a system.

### Note {#note}

The Delete System link in the upper right of this screen refers to the system profile only. Deleting a host system profile will not destroy or remove the registration of guest systems. Deleting a guest system profile does not remove it from the list of guests for its host, nor does it stop or pause the guest. It does, however, remove your ability to manage it via SUSE Manager.

If you mistakenly deleted a system profile from SUSE Manager, you may re-register the system using the bootstrap script or **rhnreg_ks** manually.

The Details page has numerous subtabs that provide specific system information and other identifiers unique to the system. The following sections discuss these tabs and their subtabs in detail.