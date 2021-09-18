# TwitterBotDMs
This short repository uses the Twitter API and tweepy module to send a direct message to the last person who followed you. 

The 'user_id.txt' file is blank. Once you run the program once it will write the user id for your most recent follower. As the script continues to run and you gain another follower, your file will change. You can adjust the bot to store the previous followers, and remove ones who have unfollowed.

If your Twitter account is very large and popular, you will need to adjust the integer passed through the time.sleep() function on line 57. 30 seconds is too long of a window. You will face complications with Twitter API's rate limited, however.
