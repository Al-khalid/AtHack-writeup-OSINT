# writeup


- 1 OSINT {Rick's House - HARD} The challenge description tells you that there this guy called Rick Evelyn and they told you to find his house










- 2 The first thing I did was google his name Rick Evilyn found a youtube channel it has two videos  

 ![clarification](https://github.com/Al-khalid/AtHack-writeup-OSINT/blob/master/2.jpg)

- 3 I thought it was just a waste of time The idea of the search came to my mind came I tried to use tools, sites, and methods to search for an account with this name

 ![clarification](https://raw.githubusercontent.com/Al-khalid/AtHack-writeup-OSINT/master/3.jpg)


- 4 Gadgets and sites gave me a lot of accounts like his Instagram account, it had 5 photos, one of them was obviously the mouse pointer in the photo, I skipped that photo and looked at the other photos I do a reverse image search, it wasn't ok, so I started googling for text in images and found 





- 5  that all other 3 pics are in Tunisia - Ariana anyway I wasted too much time on Maps and Google Earth after searching more and more I thought google maps so I searched again and again







- 6 I found the Twitter account @reviltn
 which is basically a waste of time  anyway I started searching photo sites about his username after searching I remember flicker which allows you to upload images with their original EXIF so I went to http://flicker.com and looked for
 

 ![clarification](https://raw.githubusercontent.com/Al-khalid/AtHack-writeup-OSINT/master/1.jpg)
 
 
 - 7 I found rick eviltn he has with 4 photos I downloaded them and used ExifTool to get its info but it was useless it had no location or anything so I used binwalk and found that the pics had hidden videos inside so I extracted them using binwalk -e photo_name 

![clarification](https://raw.githubusercontent.com/Al-khalid/writeup/master/Screenshot%202021-12-04%20004235.jpg?token=AV6I5XB2L5D5BFNJQ7LY7X3BVKJJM)
 - 8 anyhow the videos was another rabbit hole it was a video of "Rick" censoring people faces which were useless so while looking at flicker I found it has a map function so I used it and moved to where all the images were taken and boom




 - 9 the flag was simply the building name as they said AtHackCTF{Residence-Les-Violettes} and that's it thanks for reading wish that you had fun



![clarification](https://raw.githubusercontent.com/Al-khalid/writeup/master/8.jpg?token=AV6I5XGBODCOZX7BFXH5YTTBVKJQM)












   
