# DirectAdmin Incremental Sync Backup
#### Created by ToadSoftware.nl
Welcome to this repository of an unofficial DirectAdmin plugin called: **DA (DirectAdmin) Incremental Sync Backup**. With this plugin you can create incremental backups for your DirectAdmin users on a local or remote (with SSH) location. We use this GitHub repository to publicly track and solve user problems.

## License
Access and use the plugin through a low-cost monthly or annual subscription. Your subscription includes a license for one server identified by your server ip address and a provided token. Want to see and test before buying? No problem! You can test the plugin with a 7-day trial. [Register for a free 7-day trial here](http://www.directadminbackup.com)

## Download stable version
[Download the latest stable version here](http://toadsoftware.nl/apps/toad-dabackup/versions/latest.zip)

## Requirements
- DirectAdmin **1.4 or higher**
- PHP **5.3 or higher**
- "allow_url_fopen" enabled in PHP
- Active license or trial with license token [Register for a free 7-day trial here](http://www.directadminbackup.com)
- Ioncube (Version **4.0** or greater of the ionCube Loader is required)
 
## Installing
**1.** Copy the contents of the downloaded plugin to the DirectAdmin plugin directory:
> /usr/local/directadmin/plugins

**2.** To install the plugin, run the following commands from shell:
```
chown diradmin:diradmin -hR /usr/local/directadmin/plugins/toad-dabackup/
cd /usr/local/directadmin/plugins/toad-dabackup/scripts/
sh ./install.sh
```
**3.** You can now manage the plugin from your DirectAdmin admin account

## Changelog
**v1.2** - April 4, 2016
- Lowered requirements for ionCube loader
- Version 4.0 or greater of the ionCube Loader is required (was version 5.0)
- Updated manual backup
- Minor bug fixes

**v1.1** - March 30, 2016
- Added custom SSH port support
- New settings admin page
- Minor bug fixed

**v1.0** - March 17, 2016
- Released first full version of the plugin with a brand new one-page website

## Coming next releases
- Multiple account restore with one command
- User account exclusion (choose which account not to backup)
- Simple manual backup script
- CPU Limiter

## Questions?
Before contacting us check our [Wiki Page](https://github.com/TOAD-Joey/TOAD-DA-Sync-Backup/wiki) to see most common questions and answers. Need help with your installation or settings? 
[Contact us!](http://directadminbackup.com)
