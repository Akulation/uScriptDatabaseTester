# uScriptDatabaseTester


## How to install uScript2
- 1. Download the latest uScript2 release from this discord server, https://discord.gg/kUvDKBnzyz
- 2. Extract uScript2.zip into your root Unturned directory
- 3. Restart your server

## How to configure database with uScript2 (guide for pterodactyl panel, most hosts use this panel)
- 1. Create a new database for testing
- 2. Go to your file manager and go to this folder: `Servers/YourServer/uScript`
- 3. Open the `uScript_config.yaml` file
- 4. Add in your database details
- 5. Restart your server

## How to test if uScript2 and database works correctly
- 1. Download the latest release of uScriptDatabaseTester (all you need is the .uscript file)
- 2. Put the `uScriptDatabaseTester.uscript` file into your scripts folder located at `Servers/YourServer/uScript/Scripts`
- 3. Use `/script reload` or restart your server
- 4. If any errors occur then you have some sort of issue with uScript2 or your database

### Common Errors

**Database Issue**
- I literally dont know why this occurs or how to fix it, sorry.
```
Error in uScriptDatabaseTester.uscript
-> Line: 5
-> Column: 22
-> Info: One or more errors occurred.
StackTrace:
        at event_@onLoad_0() line 5, column 22
```

**Database not set up correctly**
- Make sure your database details are correct and there are no spaces after each thing.
```
Error in test.uscript
-> Line: 5
-> Column: 22
-> Info: Unable to connect to any of the specified MySQL hosts.
StackTrace:
        at event_@onLoad_0() line 5, column 22
```
