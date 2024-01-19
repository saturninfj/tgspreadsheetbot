# tgspreadsheetbot
With this script, you can a bot that mirror your info whenever you post on a google spreadsheet.

Here's a guide step-by-step:

1. Make a new bot from https://t.me/BotFather
2. Make sure to keep the bot token safe. You'll need this later.
3. Now, go to your telegram group to get the group id. (The one that will be accessed by the bot to mirror any information from the google spreadsheet)
   Do this by accessing your telegram via web.telegram.org, click the group, and then in the url there is a number starts with "-". (That's the group id)
5. Now use go to your google spreadsheet doc, go to "Extensions" -> "Apps Script"
6. Make a new script, then paste script provided from this doc
7. In the script, edit the bot token and telegram id with yours.
8. Save the script, and run it
9. In the Apps script site, go to "Triggers" tab.
10. Click add triggers.
    
11.
Which function to run:
myFunction

Which runs at deployment:
Head

Select event source:
From spreadsheet

Select event type:
On edit

Failure notification settings:
Notify me immediately

Hit save.

12. Now, in your telegram group invite the bot and add it as admin.
13. Try writing in the spreadsheet, see if the bot tell the same on the telegram

Enjoy.
