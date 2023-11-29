# Rust Server Plugins + Oxide Perms Starting

## Main Plugins Here:

- https://umod.org/plugins/gather-manager
- https://umod.org/plugins/time-of-day		// for short nights
- https://umod.org/plugins/clear-night
- https://umod.org/plugins/discord-auth
- https://umod.org/plugins/quick-smelt
- https://umod.org/plugins/stack-size-controller
- https://umod.org/plugins/better-loot		// for barrels and shit and crates
- https://umod.org/plugins/better-chat		// to see mods and admins in chat
- https://umod.org/plugins/crafting-controller		// quicker crafting
- https://umod.org/plugins/fancy-drop
- https://umod.org/plugins/loading-messages		// advertise discord
- https://umod.org/plugins/unburnable-meat
- https://umod.org/plugins/advert-messages
- https://umod.org/plugins/wounded-screams
- https://umod.org/plugins/info-panel
- https://umod.org/plugins/server-info
- https://umod.org/plugins/welcome-screen
- https://umod.org/plugins/image-library
- https://umod.org/plugins/compound-options
- https://umod.org/plugins/quick-sort
- https://umod.org/plugins/clans

### Moderator Plugins:
- https://umod.org/plugins/vanish
- https://umod.org/plugins/better-chat-mute
- https://umod.org/plugins/admin-panel		// 9 months old
- https://umod.org/plugins/remover-tool
- https://umod.org/plugins/godmode
- https://umod.org/plugins/admin-logger
- https://umod.org/plugins/player-administration			// 30 days old


### Donator Options below:
https://umod.org/plugins/active-sort
https://umod.org/plugins/furnace-splitter
https://umod.org/plugins/skins
https://umod.org/plugins/rust-kits
https://umod.org/plugins/wipe-kits
Skinbox - already added


### Optional Plugins: (ideas to build from)
https://umod.org/plugins/godmode
https://umod.org/plugins/backpacks		// maybe for donators
https://umod.org/plugins/skip-night-vote
https://umod.org/plugins/magic-panel
https://umod.org/plugins/loading-messages
https://umod.org/plugins/dangerous-treasures
https://umod.org/plugins/raidable-bases
https://umod.org/plugins/friends
https://umod.org/plugins/chat-notice		// Sound effect for receiver messages.
https://umod.org/plugins/discord-server-stats
https://umod.org/plugins/bounty		// Put a bounty on the clan in first place.
https://umod.org/plugins/raid-alarm
https://umod.org/plugins/clear-repair


---


## Already added plugins: (Please move to here after)


In game run this:

oxide.version		// to see oxide version

moderatorid 76561198106966240		// to add someone to moderator (rust moderator not oxide)
 
server.writecfg		(write rust server config and not oxide use one below to reload oxide plugin configs)
  
log off and back on to the server to be granted their new roles
 
**RELOAD OXIDE PLUGIN CONFIGS:
oxide.reload QuickSmelt
oxide.grant group default quicksmelt.use


---

## Permissions and groups:

oxide.show groups

oxide.grant group admin skinbox.use
oxide.grant group vip skinbox.use
oxide.grant group admin skinbox.admin

oxide.grant group admin permissionsmanager.allowed

oxide.show perms ‘group_name’		// to see perms of a group
oxide.show group admin			// to see users of a group
oxide.usergroup add <player_name or STEAM64_ID> group_name
oxide.usergroup remove <player_name or STEAM64_ID> group_name
oxide.revoke group admin coolplugin.use
oxide.group add supporters
oxide.group set supporters “[Server Supporters]”	// Group title set
oxide.group set supporters “[Server Supporters]” 1		// Change group rank
oxide.group parent tier_2 tier_1		// can also tier the groups for vip gold and vip diamond so auto add perms from lower group
oxide.grant user <user_name or STEAM64_ID> <permission>
oxide.revoke user <user_name or STEAM64_ID> <permission>
oxide.show user user_name		// show players assigned perms
oxide.show perm coolplugin.use		// show who is assigned to that perm
