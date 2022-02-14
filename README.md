# fox-tracker 
<img src="https://media.discordapp.net/attachments/777935642004553792/942833728672129094/senko_dub.png?width=1202&height=676">

## Description
a funny little project to track users on discord
Now includes/is planning to add functions to track user activity in general and aims to track sleep schedules, spotify activity and more.

## Dependencies

-   `discord.py`  -- library to interact with the discord API
-   `json`        -- to read json files (config & secret)
-   `asyncio`     -- to run code asynchronously 
-   `datetime`    -- time related items

## Functions

- log all user statuses on initialization + continue to log changes in user activity

## TODOs
1. fix bug with custom status and logging
2. add discord status tracking functions (online, dnd, idle, offline)
3. base sleep tracker on discord status tracking
4. upload logged statistics to a server, whether that is to a google spreadsheet or to a personal server via ssh & scp
5. clean up code (rewrite main and commands.cog), clean up events
6. graph data just for the sake of it
7. do some cool stuff with it maybe 
8. clean the code its spaghetti rn

## License
GPL 3.0

## Contributors
suwa
