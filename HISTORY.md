1.4.0 / 2014-08-12
==================
- Changed: Add defaults for $_from and $_reply_to
- Changed: Test mode only changes explicitly overridden values
- Improved: Module respects original error capture state

1.3.0 / 2014-01-29
==================
- Enhanced: testing mode more configurable, includes optional warning dialog
- Changed: use dedicated test email account
- Fixed: bug where default settings weren't respected

1.2.1 / 2014-01-18
==================
- Changed: clear configuration settings

1.2.0 / 2014-01-17
==================
- Enhanced: support extended ascii characters (anything over 127)

1.1.3 / 2014-01-07
==================
- Changed: fork Navigation module, now at v1.0.4
- Changed: rename Navigation table to Solution

1.1.2 / 2014-01-03
==================
- Fixed: bug validating navigation to plug-in layout when installing plug-in

1.1.1 / 2013-12-24
==================
- Docs:  new history file and convention

1.1.0 / 2013-12-20
==================
- Added:  sends plain text alternative when html body is present
- Added:  $_hostname parameter to email
- Changed:  uses TLS by default when authenticating
- Improved:  more inclusive reporting of error messages

1.0.0 / 2013-12-16
==================
- Added:  installs plug-in
- Added:  tests for supported platform
- Improved:  error capturing and reporting
- Improved:  converts attachment paths for user (removing prefix and disk name)
- Fixed:  problem sending messages with trailing delimiter in address or attachment lists

0.2.0 / 2013-12-10
==================
- Added:  $_reply_to parameter to email
- Fixed:  inability to send attachments

0.1.0 / 2013-11-26
==================
- Initial release