# DirectAdmin Incremental Sync Backup
#### Created by ToadSoftware.nl
Welcome to this repository of an unofficial DirectAdmin plugin called: **DA (DirectAdmin) Incremental Sync Backup**. With this plugin you can create incremental backups for your DirectAdmin users on a local or remote (with SSH) location. We use this GitHub repository to publicly track and solve user problems.

## License
Access and use the plugin through a low-cost monthly or annual subscription. Your subscription includes a license for one server identified by your server ip address and a provided token. Want to see and test before buying? No problem! You can test the plugin with a 7-day trial. 

## Requirements
- DirectAdmin 1.4 higher
- PHP 5.3 higher
- "allow_url_fopen" enabled in PHP
- Active license or trial with license token
- Ioncube
 
## Installing
**1.** Copy the contents of the downloaded plugin to the DirectAdmin plugin directory:
> /usr/local/directadmin/plugins

**2.** To install the plugin, run the following command from shell:
```
chown diradmin:diradmin -hR /usr/local/directadmin/plugins/toad-dabackup/
cd /usr/local/directadmin/plugins/toad-dabackup/scripts/
sh ./install.sh
```
**3.** You can now manage the plugin from your DirectAdmin admin account
