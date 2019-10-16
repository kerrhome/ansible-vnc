
* Cleanup
   * Fixed permissions on service file to eliminate warnings on startup
   * Fixed `become` when creating the user's .vnc session config file
   * Use a handler instead of task to only execute password gen script if there was a change to the script or default password 

* Forked and updated to support:
    * newer Ansible API
    * systemd
    * multiple distributions (e.g. Ubuntu, Debian)
    * only copy files when there is an update (report 'ok' otherwise)
    * switch to lxde.
