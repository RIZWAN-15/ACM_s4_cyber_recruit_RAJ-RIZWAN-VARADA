WAND:
This task initially gave an image of wand.jpeg and asked to find the flag from the image

As image is given I tried binwalk command I found no clue 
so I tried strings command (strings wand.jpeg) and I found dpass: and a clue related to harry potter 
as i dont have knowledge related to harrypotter I searched in web and i found the password is the full name of dumbledore

The clue also tells that there exist some file and the password for that file is: albuspercivalwulfricbriandumbledore

later By this clue I tried the command (steghide info wand.jpeg)
and (steghide extract -sf wand.jpeg)
Then I entered the password and a hide.txt file is saved in the system

This hide.txt is the flag

final flag= potter{1_570l3_7h47_3ld3r_w4nd}


