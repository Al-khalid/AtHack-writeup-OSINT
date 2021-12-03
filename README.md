# writeup


- 1 OSINT{Rick's House - HARD} The challenge description tells you that there this guy called Rick Evelyn and they told you to find his house










- 2 First things i did was google his name Rick Eviltn 
found a youtube channel it had two videos and they had 0 views at the time of the contest first thing that came to my mind bingo frame by frame or sound reverse did that but sadly nothing i didnt watch the other video ---


![clarification](https://raw.githubusercontent.com/Al-khalid/writeup/master/2.jpg?token=AV6I5XD6XXRKWLCQGBADO3TBVKI22)

- 3 cuz it was 3 mins and I thought it was just a waste of time The idea of the search came to my mind came I tried to use tools, sites, and methods to search for an account with this name




- 4 Gadgets and sites gave me a lot of accounts like his Instagram account, it had 5 photos, one of them was obviously the mouse pointer in the photo, I skipped that photo and looked at the other photos I do a reverse image search, it wasn't ok, so I started googling for text in images and found 





- 5  that all other 3 pics are in Tunisia - Ariana anyway I wasted too much time on Maps and Google Earth after searching more and more I thought google maps so I searched again and again







- 6 I found twitter account @reviltn
 which is basically a waste of time  anyway I started searching photo sites about his username after searching I remember flicker which allows you to upload images with their original EXIF so I went to http://flicker.com and looked for
 
![clarification](https://raw.githubusercontent.com/Al-khalid/writeup/master/1.jpg?token=AV6I5XDPBRDA7ZEW32VRB3TBVKIS4)
 
 
 
 - 7 I found rick eviltn you have with 4 photos downloaded them and used ExifTool to get its info but it was useless it had no location or anything so I used binwalk and found that the pics had hidden videos inside so I extracted them using binwalk -e photo_name 


 - 8 anyhow the videos was another rabbit hole it was a video of "Rick" censoring people faces which were useless so while looking at flicker I found it has a map function so I used it and moved to where all the images were taken and boom




 - 9 the flag was simply the building name as they said AtTack CTF{Residence-Les-Violettes} and that's it thanks for reading wish that you had fun as I did















   
