# launchd-examples

## How to run/use
* cd to one of the launchd folders. It can be -> $HOME/Library/LaunchAgents | /Library/LaunchAgents | /Library/LaunchDaemons
* run this: `launchctl load com.dzmitryh.cronlike.job.plist`
* verify if it's running: launchctl list | grep com.dzmitryh.cronlike.job
* if u need to apply new changes use this `lctl reload com.dzmitryh.cronlike.job.plist` (custom script from here -> https://github.com/dzmitryh/dotfiles/blob/23981ce1d825f3bb6588527dc253f4e8d786143f/zsh/functions.zsh#L43)
