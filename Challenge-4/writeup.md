This is for you know who:
this task initially gives a zip folder 

Initially I extracted the folder I ound only a txt file and After few tries I tried to search in hidden files then later i found an image 
from the image i used binwalk command and I found some zip folder and extracted it again I repeated the similar steps and finally I found the image horcrux.jpg 

I used strings to read the horcrux.jpg and I finally found the base64 format text inside the image

later the base64 decode I found the final flag;

final Flag=potter{7h15_15_D010r35_Um8r1dg3}
