# Spotify Discovery Saver 
Spotify offers users a discovery playlist which is updated every Monday with 50 unheard 
songs which are tailored to each user's listening history. However, these songs are deleted
at the end of every week and impossible to restore. 

This Python program utilizes the Spotify API to automatically save all the songs from your 
discover weekly playlist, create a new playlist, and store them so you can keep them even after
the end of the week. It also refreshes your API access token so you do not have to edit the 
program even after the token expires every hour. 

Example playlist:
![example-image](https://github.com/ericwkong/Spotify-Discover-Weekly-Saver/blob/main/Screenshot%202025-03-05%20at%209.38.22%20PM.png)

This program can be scheduled to run in the background weekly using the Windows task scheduler so
you never have to worry about losing your discovery songs again. 
