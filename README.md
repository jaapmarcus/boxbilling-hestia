# Boxbilling Hestia Module

Boxbilling Modules by Estratos edited and updated by Pctec2012 and modified by Jaapmarcus for HestiaCP  also updated Vesta version to support API keys

Box

Tested on Version: 4.22 released 2020-10-30

Put Contents of Directory bb-library/Server/Manager folder into bb-library/Server/Manager folder in Boxbilling:

Based of VestaCP Server module 2

This release includes the following actions via Hestia API

- Create new user + primary domain 
- Suspend user 
- Unsuspend user
- Cancel / Delete user 
- Change package

## Changes made:

- Added support for Hestia
- Fix bug that a user wasn't created
- Removed optional ssl option only https:// request are allowed
- Set Default port 8083 as default value
- Add support for access hash / "Api key"
 
Files:

Hestia.php must be placed on ../bb-library/Server/Manager/

## Donate 

If you are going to use this module please consider donating to HestiaCP

[HestiaCP Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ST87LQH2CHGLA)

