# Permissions and groups:

These commands can be ran in RustAdmin. "Type a command to execute", takes forever implemnting permissions this way. we need a gui or something. 
but we can just slowly give permissions for the time bing.


1st command: (To show groups so you can add members if needed, which should be needed once we get donation plugin setup. Only to make new mods/admins)
oxide.show groups

oxide.grant group admin skinbox.use
oxide.grant group vip skinbox.use
oxide.grant group admin skinbox.admin

oxide.grant group admin permissionsmanager.allowed

oxide.show perms 'group_name'		// to see perms of a group
oxide.show group admin			// to see users of a group
oxide.usergroup add <player_name or STEAM64_ID> group_name
oxide.usergroup remove <player_name or STEAM64_ID> group_name
oxide.revoke group admin coolplugin.use
oxide.group add supporters
oxide.group remove <group>
oxide.group set supporters “[Server Supporters]”	// Group title set
oxide.group set supporters “[Server Supporters]” 1		// Change group rank
oxide.group parent tier_2 tier_1		// can also tier the groups for vip gold and vip diamond so auto add perms from lower group
oxide.grant user <user_name or STEAM64_ID> <permission>
oxide.revoke user <user_name or STEAM64_ID> <permission>
oxide.show user user_name		// show players assigned perms
oxide.show perm coolplugin.use		// show who is assigned to that perm
oxide.group parent <parentgroup><childgroup>
oxide.group set <group><"[Title]"><rank>

Setting the parent group of another group. A group will inherit all permissions from its parent group.

oxide.group parent admin default



**** Don't forget to log out and back in to set permissions!


RUST GROUPS  -- NOT PART OF OXIDE

ownerid 76561198106966240     // LVL 2 auth on everything
moderatorid <your steam 64 id>    // lvl 1 auth on everything

idk what moderator entails yet, but soon will find out. No reason to give out that permission, just use oxide groups.

/perms    # Use for permission manager in game, fixed using with imagelibrary from umod
