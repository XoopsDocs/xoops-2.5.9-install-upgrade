# Upgrading

The XOOPS Upgrader examines your XOOPS installation and applies any needed
patches to make it compatible with the new XOOPS code. Patches may include
database changes, adding default settings for new configuration items,
file and data updates, and more.

The upgrader is tested against a variety of XOOPS installation, both old
and new, but the process is smoothest with the most recent XOOPS releases.
If you are upgrading a older system and need help, please visit our support
forums at https://xoops.org/modules/newbb/

## Quick Overview

 - Make a full backup of site files and database
 - It may be helpful to enable debugging in System Options - Preferences - General Settings
 - It is wise to turn your site off in System Options - Preferences - General Settings
 - Copy the contents of the distribution htdocs directory into your web root directory. Be careful not to overwrite any customize configuration or theme files.
 - Copy the contents of htdocs/xoops_lib to your relocated/renamed xoops_lib as applicable
 - Copy the distribution upgrade directory into your web root directory
 - Point your browser to *your-site-url*/upgrade/ and follow the prompts
 - Log in and step through any needed updates with the "Continue" button
 - At the end, upgrade the system module
 - Also update pm, profile and protector modules if installed
 - Don't forget to turn your site back on, if needed
