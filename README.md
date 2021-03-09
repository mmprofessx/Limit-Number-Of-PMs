### INFORMATION ###

Limit Number of PMs (1.1) for MyBB 1.8
Created by: Starpaul20
Copyright: © 2009
License: GPL

Allows Administrators to limit the number of Private Messages (PMs) that users in a specific usergroup can post in a day. If a user reaches the limit (set as a usergroup permission) they will receive an error telling them they've reached their daily PM limit.

The usergroup permission are located under the 'Private Messaging' section of the 'Users and Permissions' tab when editing a usergroup.

This plugin offers full language support.

The 'oldrelease' branch contains the 1.6 version of the plugin.


### INSTALLATION ###

1. Upload all files above, keeping the file structure intact.
2. Go to Configuration > Plugins
3. Click "Activate"
4. Enjoy!


### UPDATING ###

If you're updating from any previous version, you must first deactivate the plugin, upload all new files and reactivate.

1.1 (February 22nd, 2015)
- Added PostgreSQL and SQLite support
- Using generate_numeric_field function
- Changed (int)$mybb->input to $mybb->get_input

1.0 (September 1st, 2014)
- Updated plugin to work with MyBB 1.8

### Version number reset for MyBB 1.8 ###

2.0.4 (October 23rd, 2013)
- Bug: Fixed language error for 1.6.11

2.0.3 (November 25th, 2011)
- Dropped MyBB 1.4 support
- Updated plugin with 1.6.5 plugin system updates
- Optimization and general plugin updating

2.0.2 (August 30th, 2010)
- Bug: Fixed bug causing 'Max PM allowed Per Day' field to appear in several other sections of the Admin CP

2.0.1 (August 27th, 2010)
- Bug: Fixed error causing the 'maxpmcount' to add in PMs in the 'Sent Items' folder when checking number of PMs

2.0 (August 3rd, 2010)
- Updated plugin to work with MyBB 1.6

1.0.3 (January 14th, 2010)
- Updated location of Usergroup setting

1.0.2 (September 5th, 2009)
- Bug: Fixed error causing the 'View Manager' section to return PHP error

1.0.1 (August 27th, 2009)
- Fixed spelling error in Admin CP

1.0 (June 15th, 2009)
- Initial release
