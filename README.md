Instructions:

 
Moderation.json - Adds a moderator comment to a container / plugin.


Some special items can be added:

MinVer - Minimum OS version allowed
MaxVer - Maximum OS version allowed
Deprecated - True/False
Blacklisted - True/False
DeprecatedMaxVer - unRaid version that the template gets deprecated when on.
ModeratorComment - a comment to place within the app.  Also triggers warning on FCP
CAComment - a comment to place within the app.  Will NOT trigger a warning on FCP
RemoveFromCA - completely removes the template.  Does not trigger a deprecation or blacklist

  Note that both MinVer and MaxVer do not have to be present

PublicServiceAnnouncement:  Contents of this file are read in case of an appfeed failure and display to the user.  Edit and update accordingly during an extended outage
