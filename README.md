# PasteBin-Java-API
Java PasteBin Helper

# Get Started
For install this your only need to download it and add in your source

Now go to http://pastebin.com and create an account, then go http://pastebin.com/api and copy your Developer API Key:

![alt tag](http://image.prntscr.com/image/ae9d74414b6e4d12bab0e9761d833998.png)

Then in your start class add this
Paste.setDeveloperKey("Your Developer Key Here");

And now when you need to create a pastebin only need to do this
new Paste("Code here!", "File Name", Visibility.PUBLIC, Expire.ONE_HOUR, Language.JAVA).upload();
