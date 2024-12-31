# BASH 2.0

Note:
My version of bash is more geared toward collecting extra information and making things more presentable for the competitive strafing community. This version of bash has no new or advanced detection methods or anything of that nature, the only new auto bans added are for certain gain logs. If you want to ban users using null movement scripts, this version simply will not do it.

## If you're already using Bash2 on your server, you will need to delete your current cfg(or rename it to something like bash.cfg.bak) and let it regenerate. This version is much more configurable.

Main Changes:
* Remove useless code that was intended for the older movement community (nulls detections, faking if a player is on the ground to brick optis, etc)
* Add configurations for dev and identical strafes bans
* Add auto bans for certain ridiculous gain logs
* Add configurations for a steam group that's whitelisted from the auto bans
* Logs are more presentable/searchable

## Commands

```
sm_bash or sm_bash2 - open the bash settings menu
bash2_stats <name> - Show strafe stats
bash2_admin - toggle admin mode, lets you enable/disable printing of bash logs into the chat.
bash2_personal - toggle personal mode, lets you enable/disable only seeing your own logs in chat.
bash2_test  - trigger a test message so you can know if webhooks are working
```

## Depencenies for the Discord Messages

* [SteamWorks](https://forums.alliedmods.net/showthread.php?t=229556)
* [sm-json](https://github.com/doug919/smjson) (only for compiling)

## Anticheat bypass

If you are using shavit bhoptimer, you can add "bash_bypass" into a style's special string to disable detection for this style.
