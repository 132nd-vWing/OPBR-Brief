# WebDispatcher

## Warning: Follow these steps closely!

Because ED's implementation of LUA is a little bit... interesting, we are left with having to do a few workarounds unfortunatly:

1.  Add "mint={require=require}" to the top of your MissionScripting.lua file
2.  Make folders so that you can navigate to "C:\DCS World Open Beta\bin\lua\socket" folder
3.  Copy ALL files from "C:\DCS World Open Beta\LuaSocket" into the "socket" folder in step 2
4.  Move the files "socket.lua", "mime.lua" and "ltn12.lua" to "C:\DCS World Open Beta\bin\lua\"

NOTE! YOU WILL HAVE TO REDO STEP 1 EVERY TIME YOU UPDATE DCS!!
