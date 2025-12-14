# cvaccess
Integrate a remote credential vault with keepassxc.

- Auto mount the remote credential vault with a service.
- Make local backups.
- Conviniently access extracted backups with your password manager.

## Setup
### Ansible
`{ role: cvaccess, cvaccess_enabled_backups: true, cvaccess_users: [myuser, otheruser] }`
#### If you want keepassxc to open the remote vault automatically
Set your keepassxc launcher to execute the `/usr/local/lib/smart-keepassxc` script.
