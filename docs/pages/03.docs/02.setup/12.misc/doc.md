---
title: Misc
---
# Miscellaneous
This page contains some other miscellaneous settings that do not really fit anywhere else.

## Permissions denied message
By default GearBot will tell people when they are not authorized to execute a command, this can be disabled:
```
!configure perm_denied_message off
```
To enable it again afterwards:
```
!configure perm_denied_message on
```

# Timezones
You can configure the timezone used for logging!:
```
!configure timezone <timezone>
```
For a full list of timezones see: https://en.wikipedia.org/wiki/List_of_tz_database_time_zones . The input for the bot is listed in the ``TZ database name`` column

## DM users warnings
When you warn a user, GearBot can DM them that warning, this behaviour is disabled by default.
To enable this:
```
!configure dm_on_warn on
```

If you want to disable it again later:
```
!configure dm_on_warn off
```

